FROM ldumas/pandora_build_env:ubuntu20.04-python3.7

##
# env sphinx
RUN pip3 install ipython sphinx sphinx_rtd_theme sphinx_autoapi

##
# env latex for sphinx
RUN apt-get update && \
    apt-get install -y --no-install-recommends texlive-full && \
    apt-get install -y dvipng
