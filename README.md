# bioinformatics

mat_ag2pat = np.array([
#  ADP    Thr     TXA2    P-sel  LTB4    Ilop   NO     RvD1   RvD2   AnxA1
[  0.5,   0.6,    0.5,    0.4,   0.6,   -0.4,  -0.6,  -0.6,  -0.5,  -0.5 ],  # NFkB_core
[  0.6,   0.8,    0.7,    0.3,   0.5,   -0.4,  -0.5,  -0.5,  -0.5,  -0.4 ],  # p38_MAPK
[  0.5,   0.7,    0.6,    0.3,   0.4,   -0.3,  -0.5,  -0.4,  -0.4,  -0.3 ],  # ERK
[ -0.7,  -0.3,   -0.3,   -0.2,  -0.2,    0.9,   0.2,   0.2,   0.1,   0.1 ],  # cAMP_PKA_KLF2_eNOS
[  0.0,  -0.2,   -0.2,   -0.1,  -0.1,    0.1,   1.0,   0.1,   0.1,   0.1 ],  # sGC_cGMP_PKG
[  0.0,   0.0,    0.0,    0.0,   0.0,    0.0,   0.0,   1.0,   0.0,   0.9 ],  # ALX_FPR2_SPM
[  0.0,   0.0,    0.0,    0.0,   0.0,    0.0,   0.0,   0.0,   1.0,   0.0 ],  # GPR18_RvD2
[  0.5,   0.4,    1.0,    0.2,   0.2,   -0.3,  -0.3,  -0.2,  -0.2,  -0.2 ],  # COX_TXA2
[  0.2,   0.2,    0.1,    0.2,   1.0,   -0.2,  -0.2,  -0.4,  -0.3,  -0.3 ],  # LOX5_LTB4
[  0.1,   1.0,    0.1,    0.1,   0.0,   -0.2,  -0.2,  -0.2,  -0.2,  -0.2 ],  # PAR_signaling
[  1.0,   0.2,    0.1,    0.1,   0.0,   -0.2,  -0.2,  -0.2,  -0.2,  -0.2 ],  # P2Y12_Gi
], dtype=float)

mat_ag2pat = np.array([
    # ADP   Thr    TXA2   P-sel  LTB4   Ilop   NO     RvD1   RvD2   AnxA1
    [ 0.3,  0.4,   0.2,   0.6,   0.5,  -0.5, -0.5,  -0.6,  -0.5,  -0.6],  # NFkB_core
    [ 0.6,  0.9,   0.5,   0.2,   0.7,  -0.6, -0.5,  -0.5,  -0.4,  -0.5],  # p38_MAPK
    [ 0.6,  0.7,   0.5,   0.2,   0.6,  -0.6, -0.5,  -0.4,  -0.4,  -0.4],  # ERK
    [-0.8, -0.3,  -0.5,  -0.2,  -0.3,   1.0,  0.3,   0.2,   0.1,   0.2],  # cAMP_PKA_KLF2_eNOS
    [-0.1,  0.0,  -0.2,  -0.1,  -0.1,   0.2,  1.0,   0.1,   0.1,   0.1],  # sGC_cGMP_PKG
    [ 0.0,  0.0,   0.0,   0.0,   0.0,   0.0,  0.0,   1.0,   0.0,   1.0],  # ALX_FPR2_SPM
    [ 0.0,  0.0,   0.0,   0.0,   0.0,   0.0,  0.0,   0.0,   1.0,   0.0],  # GPR18_RvD2
    [ 0.3,  0.6,   1.0,   0.1,   0.2,  -0.5, -0.6,  -0.5,  -0.3,  -0.4],  # COX_TXA2
    [ 0.0,  0.2,   0.1,   0.0,   1.0,  -0.2, -0.2,  -0.6,  -0.4,  -0.4],  # LOX5_LTB4
    [ 0.3,  1.0,   0.2,   0.0,   0.1,  -0.4, -0.4,  -0.4,  -0.3,  -0.3],  # PAR_signaling
    [ 1.0,  0.3,   0.3,   0.0,   0.1,  -0.6, -0.5,  -0.4,  -0.3,  -0.3],  # P2Y12_Gi
], dtype=float)

mat_ag2pat = np.array([
# ADP   Thr   TXA2  P-sel  LTB4  Ilop  NO    RvD1  RvD2  AnxA1
[ 0.3,  0.8,  0.7,  0.6,   0.7, -0.6, -0.6, -0.7, -0.7, -0.6],   # NFkB_core
[ 0.5,  0.6,  0.5,  0.2,   0.6, -0.3, -0.2, -0.4, -0.4, -0.3],   # p38_MAPK
[ 0.4,  0.6,  0.4,  0.2,   0.5, -0.2, -0.1, -0.3, -0.3, -0.2],   # ERK
[-0.7, -0.3, -0.4, -0.2,  -0.4,  0.9,  0.3,  0.2,  0.2,  0.1],   # cAMP_PKA_KLF2_eNOS
[-0.4, -0.3, -0.5, -0.1,  -0.3,  0.3,  0.9,  0.2,  0.2,  0.1],   # sGC_cGMP_PKG
[ 0.0, -0.1, -0.2, -0.2,  -0.3,  0.2,  0.2,  0.9,  0.3,  0.9],   # ALX_FPR2_SPM
[ 0.0, -0.1, -0.2, -0.2,  -0.3,  0.1,  0.1,  0.3,  0.9,  0.2],   # GPR18_RvD2
[ 0.5,  0.6,  0.9,  0.2,   0.2, -0.5, -0.5, -0.6, -0.5, -0.5],   # COX_TXA2
[ 0.2,  0.3,  0.2,  0.4,   0.9, -0.3, -0.3, -0.5, -0.5, -0.4],   # LOX5_LTB4
[ 0.1,  0.95, 0.3,  0.0,   0.1, -0.3, -0.2, -0.3, -0.3, -0.3],   # PAR_signaling
[ 0.95, 0.2,  0.3,  0.0,   0.1, -0.6, -0.4, -0.2, -0.2, -0.2],   # P2Y12_Gi
], dtype=float)




























mat_pat2mark = np.array([
# VCAM1  ICAM1  SELE   IL6
[  0.9,   0.8,   0.7,   0.9 ],  # NFkB_core → strong induction of adhesion molecules & IL-6
[  0.6,   0.6,   0.5,   0.7 ],  # p38_MAPK → pro-inflammatory transcription
[  0.5,   0.5,   0.5,   0.6 ],  # ERK → pro-inflammatory support
[ -0.8,  -0.7,  -0.7,  -0.6 ],  # cAMP_PKA_KLF2_eNOS → atheroprotective; KLF2/NO suppress adhesion genes
[ -0.7,  -0.7,  -0.6,  -0.6 ],  # sGC_cGMP_PKG → NO signaling lowers adhesion & cytokines
[ -0.6,  -0.6,  -0.5,  -0.6 ],  # ALX_FPR2_SPM → specialized pro-resolving mediators
[ -0.5,  -0.5,  -0.4,  -0.5 ],  # GPR18_RvD2 → pro-resolving, anti-NFκB/MAPK
[  0.6,   0.6,   0.5,   0.5 ],  # COX_TXA2 → pro-inflammatory tone
[  0.6,   0.6,   0.5,   0.6 ],  # LOX5_LTB4 → pro-inflammatory tone
[  0.6,   0.6,   0.5,   0.6 ],  # PAR_signaling → pro-inflammatory tone
[  0.5,   0.5,   0.4,   0.5 ],  # P2Y12_Gi → pro-inflammatory/anti-cAMP influence on endothelium
], dtype=float)

mat_pat2mark = np.array([
    #  NFkB  p38   ERK   cAMP   sGC   ALX   GPR18  COX   LOX5  PAR   P2Y12
    [  0.9,  0.4,  0.3, -0.7, -0.6, -0.6, -0.5,  0.5,  0.5,  0.5,  0.6],  # VCAM1
    [  0.9,  0.4,  0.3, -0.6, -0.6, -0.5, -0.4,  0.5,  0.5,  0.5,  0.6],  # ICAM1
    [  0.8,  0.3,  0.3, -0.6, -0.5, -0.5, -0.4,  0.4,  0.4,  0.4,  0.5],  # SELE (E-selectin)
    [  0.8,  0.5,  0.5, -0.5, -0.5, -0.5, -0.4,  0.5,  0.5,  0.6,  0.5],  # IL6
], dtype=float)

mat_pat2mark = np.array([
# VCAM1 ICAM1 SELE  IL6
[ 0.9,   0.9,  0.8,  0.9],   # NFkB_core
[ 0.6,   0.6,  0.6,  0.7],   # p38_MAPK
[ 0.4,   0.3,  0.4,  0.5],   # ERK
[-0.8,  -0.2, -0.8, -0.6],   # cAMP_PKA_KLF2_eNOS  (KLF2 axis: strong ↓VCAM/E-selectin; modest effect on ICAM)
[-0.7,  -0.7, -0.5, -0.6],   # sGC_cGMP_PKG        (NO/PKG broadly anti-inflammatory)
[-0.7,  -0.7, -0.6, -0.7],   # ALX_FPR2_SPM        (RvD1/AnxA1 via ALX/FPR2)
[-0.6,  -0.6, -0.5, -0.7],   # GPR18_RvD2
[ 0.6,   0.6,  0.6,  0.6],   # COX_TXA2            (TXA2/TP signaling)
[ 0.6,   0.6,  0.5,  0.7],   # LOX5_LTB4
[ 0.7,   0.7,  0.8,  0.7],   # PAR_signaling       (thrombin/PAR)
[ 0.3,   0.3,  0.3,  0.3],   # P2Y12_Gi            (platelet Gi axis → net pro-inflammatory milieu)
], dtype=float)
