# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Difference-in-differences based on inverse probability weighting Use didweight (causalweight) With (In) R Software
install.packages("causalweight")
library("causalweight")
didweight = read.csv("https://raw.githubusercontent.com/timbulwidodostp/didweight/main/didweight/didweight.csv",sep = ";")
# Estimation Difference-in-differences based on inverse probability weighting Use didweight (causalweight) With (In) R Software
y = didweight$y
d = didweight$d
t = didweight$t
x = didweight$x
didweight <- didweight(y = y, d = d, t = t, x = x, boot = 199)
didweight
# Difference-in-differences based on inverse probability weighting Use didweight (causalweight) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished