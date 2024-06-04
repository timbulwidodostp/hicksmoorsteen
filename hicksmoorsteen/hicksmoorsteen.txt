# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Hicks-Moorsteen productivity and profitability index Use hicksmoorsteen (productivity) With (In) R Software
install.packages("productivity")
library("productivity")
hicksmoorsteen=read.csv("https://raw.githubusercontent.com/timbulwidodostp/hicksmoorsteen/main/hicksmoorsteen/hicksmoorsteen.csv",sep=";")
# Estimation Hicks-Moorsteen productivity and profitability index Use hicksmoorsteen (productivity) With (In) R Software
# Hicks-Moorsteen productivity, without price information
hicksmoorsteen_1<-hicksmoorsteen(data=hicksmoorsteen,id.var="States",time.var="Years",x.vars=c(7:10),y.vars=c(4:6),rts="crs",orientation="in")
hicksmoorsteen_1
hicksmoorsteen_2<-hicksmoorsteen(data=hicksmoorsteen,id.var="States",time.var="Years",x.vars=c(7:10),y.vars=c(4:6),w.vars=c(14:17),p.vars=c(11:13))
hicksmoorsteen_2
# Hicks-Moorsteen productivity and profitability index Use hicksmoorsteen (productivity) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished