FROM jupyter/r-notebook
# FROM rocker/r-ver:4.1.2

# # [Option] Install zsh
# ARG INSTALL_ZSH="true"
# # [Option] Upgrade OS packages to their latest versions
# ARG UPGRADE_PACKAGES="false"

# # Install needed packages and setup non-root user. Use a separate RUN statement to add your own dependencies.
# ARG USERNAME=docker
# ARG USER_UID=1000
# ARG USER_GID=$USER_UID
# COPY library-scripts/*.sh /tmp/library-scripts/
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && /bin/bash /tmp/library-scripts/common-debian.sh "${INSTALL_ZSH}" "${USERNAME}" "${USER_UID}" "${USER_GID}" "${UPGRADE_PACKAGES}" \
#     && apt-get -y install libzip-dev \
#     && apt-get autoremove -y && apt-get clean -y && rm -rf /var/lib/apt/lists/* /tmp/library-scripts

# # [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update \
#     && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends libcurl4-openssl-dev \
#     libssl-dev \
#     libxml2-dev \
#     python3-pip \
#     libxt6

# RUN python3 -m pip install setuptools
# RUN python3 -m pip install radian
# RUN python3 -m pip install jupyterlab

# RUN R -e "install.packages('IRkernel',dependencies=TRUE, repos='http://cran.rstudio.com/')"


