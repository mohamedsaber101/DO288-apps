from registry.redhat.io/rhoar-nodejs/nodejs-10

USER 0
RUN sed -i 's/#do not fail/echo sir here is NPM  $npm_config_registry /g' /usr/libexec/s2i/assemble && cat /usr/libexec/s2i/assemble
