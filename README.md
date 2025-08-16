# INIT SUBMODULES

git submodule init

git submodule update

git submodule update --init --recursive

# BUILD

docker compose build --no-cache

docker compose up -d

# BRING IT DOWN

docker compose down