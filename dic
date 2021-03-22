# CARREGANDO OS DADOS
str(dados)
attach(dados)


# ANÁLISE DOS DADOS
library(ExpDes.pt)
mod=dic(cultivar, peso, mcomp = "tukey")


# PRESSUPOSIÇÕES
library(car) 
#leveneTest(peso,cultivar,center=mean)
leveneTest(mod$res,cultivar,center=mean)

shapiro.test(mod$res)
