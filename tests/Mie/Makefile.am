pkgdatadir = $(datadir)/scuff-em/tests/Mie
pkgdata_DATA = OmegaFile				\
               EPFile					\
               LossySphere_327.scuffgeo			\
               Sphere_327.msh				\
               Checklist.DSIPFT				\
               Checklist.EMTPFT				\
               Checklist.Moments			\
               Checklist.EPFile.total

referencedir = $(pkgdatadir)/reference
reference_DATA = reference/LossySphere_327.DSIPFT       \
                 reference/LossySphere_327.EMTPFT       \
                 reference/LossySphere_327.Moments      \
                 reference/LossySphere_327.EPFile.total \
                 reference/LossySphere_327.Runtime

pkgdata_SCRIPTS = TestMie.sh
TESTS = TestMie.sh
