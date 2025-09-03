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
