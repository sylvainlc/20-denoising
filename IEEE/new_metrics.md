OURS ON SYNTHETIC NOISE (BW: BSD68)
P30: raw 18.54/0.3525, pred 28.18/0.8024
G25: raw 20.17/0.3819, pred 28.92/0.8217

OURS ON SYNTHETIC NOISE (COLOR: TRAIN BSD500)
P30
CBSD raw=18.81/0.4560, pred=29.30/0.8592
Kodak24: raw=18.65/0.3835 pred=30.61/0.8695

OTHERS
Neigh2Neigh: 31.44/0.870
Laine mu: 30.19 / 0.833
Laine-pme: 31.67/0.874
N2V: 28.9/0.788
Self2Self: 30.31/0.857

G25
CBSD:raw=20.17/0.4892, pred=30.06/0.8702
Kodak24: raw=20.17/0.4173, pred=31.48/0.8799


# EN ANNEXE FMD
OURS ON FMD:
C-MICE: raw 29.38/0.6657
G1: 38.48/0.9655
G2: 38.50/0.9660
G3: 38.15 / 0.9635
C-FISH: raw 22.81/0.4416
G1: 32.56/0.8822
G2: 32.27 / 0.8677
G3: 32.23 / 0.8603

FBI-DENOISER ON FMD:
C-MICE: 38.32/0.9637
C-FISH: 32.22/0.8853

NEIGH2NEIGH ON OUR DATASETS

W2S-1: PSNR: raw=21.85, pred=34.74 | SSIM: raw=0.3490 pred=0.9552
W2S-2: PSNR: raw=19.33, pred=32.96 | SSIM: raw=0.2256 pred=0.8739
W2S-3: PSNR: raw=20.40, pred=36.14 | SSIM: raw=0.2232 pred=0.9216

PN2V-C: 34.42 / 0.9519
PN2V-MN: 34.01/0.9070
PN2V-MA: 32.70 / 0.8521

PARAMETERS:
gamma = 1 (code: lambda1=1 & lambda2=2) (also tried gamma = 2)
lr 3e-4 (also tried 1e-4)
n_epochs = 1000 (also tried 100)
number of decays = 4 (also tried 8)

FBI ON OUR Dataset
PN2V-C: 36.23/0.9556
PN2V-MN: 36.85/0.9609 # 2 runs same result
PN2V-MA: 32.89/0.8344
W2S-1: 34.21/0.9456 or $34.40$ / $0.9500$ (100 ep)
W2S-2 $32.26$ / $0.8452$
W2S-3: $34.94$ / $0.8910$