# circle.yml
checkout:
  post:
    - git submodule sync
    - git submodule update --init
circle.yml
