# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Conservative SGoF multiple testing procedure Use SGoF (sgof) With (In) R Software
install.packages("sgof")
library("sgof")
SGoF = read.csv("https://raw.githubusercontent.com/timbulwidodostp/SGoF/main/SGoF/SGoF.csv",sep = ";")
# Estimation Conservative SGoF multiple testing procedure Use SGoF (sgof) With (In) R Software
SGoF<-SGoF$SGoF
SGoF<-SGoF(SGoF)
summary(SGoF)
plot(SGoF)
# Conservative SGoF multiple testing procedure Use SGoF (sgof) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished