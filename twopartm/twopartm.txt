# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Two-part models Use twopartm (tpm) With (In) R Software
install.packages("twopartm")
library("twopartm")
twopartm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/twopartm/main/twopartm/twopartm.csv",sep = ";")
# Estimation Two-part models Use twopartm (tpm) With (In) R Software
tpm_logit_1 = tpm(wage~educ+age+married+children, data = twopartm,link_part1 = "logit",family_part2 = Gamma)
summary(tpm_logit_1)
tpm_logit_2 = tpm(wage~educ+age+married+children, data = twopartm,link_part1 = "logit",family_part2 = poisson)
summary(tpmodel19)
tpm_probit_1 = tpm(wage~educ+age+married+children, data = twopartm,link_part1 = "probit",family_part2 = Gamma)
summary(tpm_probit_1)
tpm_probit_2 = tpm(wage~educ+age+married+children, data = twopartm,link_part1 = "probit",family_part2 = poisson)
summary(tpm_probit_2)
# Two-part models Use twopartm (tpm) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished