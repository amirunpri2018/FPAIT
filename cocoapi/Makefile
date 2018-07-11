all:
    # install pycocotools locally
	${PYTHON} setup.py build_ext --inplace
	rm -rf build

install:
	# install pycocotools to the Python site-packages
	${PYTHON} setup.py build_ext install
	rm -rf build
