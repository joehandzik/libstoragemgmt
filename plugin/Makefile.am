SUBDIRS=simc megaraid hpsa arcconf

plugindir = $(pythondir)/lsm/plugin

plugin_PYTHON= __init__.py

simdir = $(plugindir)/sim
sim_PYTHON = \
	sim/__init__.py \
	sim/simulator.py \
	sim/simarray.py

targetddir = $(plugindir)/targetd
targetd_PYTHON = \
	targetd/__init__.py \
	targetd/targetd.py

ontapdir = $(plugindir)/ontap
ontap_PYTHON = \
	ontap/__init__.py \
	ontap/ontap.py \
	ontap/na.py

smispydir = $(plugindir)/smispy
smispy_PYTHON = \
	smispy/__init__.py \
	smispy/smis.py \
	smispy/utils.py \
	smispy/smis_common.py \
	smispy/dmtf.py \
	smispy/smis_cap.py \
	smispy/smis_sys.py \
	smispy/smis_pool.py \
	smispy/smis_disk.py \
	smispy/smis_ag.py \
	smispy/smis_vol.py \
	smispy/WBEM.py \
	smispy/lmiwbem_wrap.py

nstordir = $(plugindir)/nstor
nstor_PYTHON = \
	nstor/__init__.py \
	nstor/nstor.py

dist_bin_SCRIPTS= \
	sim/sim_lsmplugin \
	smispy/smispy_lsmplugin \
	nstor/nstor_lsmplugin \
	ontap/ontap_lsmplugin \
	targetd/targetd_lsmplugin

EXTRA_DIST = \
	sim/sim_lsmplugin.in \
	smispy/smispy_lsmplugin.in \
	nstor/nstor_lsmplugin.in \
	ontap/ontap_lsmplugin.in \
	targetd/targetd_lsmplugin.in
