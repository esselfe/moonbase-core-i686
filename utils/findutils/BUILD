# Disable year 2038 support since glibc is at 2.31, to be removed with glibc 2.32
OPTS+=" --disable-year2038" &&

default_build &&

mkdir -p /var/cache/locate &&
if [ -f /var/cache/locatedb ]; then
  mv /var/cache/locatedb /var/cache/locate
fi
