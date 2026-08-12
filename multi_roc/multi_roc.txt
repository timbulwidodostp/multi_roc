# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Multi-class classification Receiver Operating Characteristic (ROC) Analysis Use multi_roc (multiROC) With (In) R Software
install.packages("remotes")
remotes::install_github("WandeRum/multiROC")
library("multiROC")
# Estimation Multi-class classification Receiver Operating Characteristic (ROC) Analysis Use multi_roc (multiROC) With (In) R Software
multi_roc = read.csv("https://raw.githubusercontent.com/timbulwidodostp/multi_roc/main/multi_roc/multi_roc.csv",sep = ";")
multi_roc <- multi_roc(multi_roc)
multi_roc$AUC
# Multi-class classification Receiver Operating Characteristic (ROC) Analysis Use multi_roc (multiROC) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished