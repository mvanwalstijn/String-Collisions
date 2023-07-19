# String-Collisions
Matlab scripts for simulation of string vibrations with collisions

These are matlab implementation of numerical scehemes for simulating string vibratoisn featuring collisions developed within the paper 
"Implicit and Explicit Scehmes for Energy-Stable Simuation of String Vibrations with Collisions: Refinement, Analysis, and Comparison", 
accepted for publication in the Journal of Sound and Vibration (July 2023).

CASE STUDY LABELS
Mass-Barrier (MB): a single mass with a spring an damper,  colliding with a static barrier; to test, run test_MB.m
Hammer-String (HS): a stiff, damped string colliding with a piano hammer; to test, run test_HS.m
String-barrier (SB): an ideal string colliding with a distributed flat static barrier; to test, run test_SB.m
Sitar-Like (SL): a stiff, damped string colliding with a short curved bridge; to test, run test_sitar.m

SCHEME LABELS:
EXP: explicit scheme
IMP: nonlinearly implicit scheme
LI: linearly implicit scheme
ME: modally expanded
FD: finite-difference

For understanding the numbering (e.g. IMP-2, EXP-3) and the choice of the system parameters, please consult the JSV paper.

