FROM alpine
COPY src/env_var_echo.sh /env_var_echo.sh
ARG buildtime_var=default_dan
ENV my_env_var=$buildtime_var
CMD ["/env_var_echo.sh"]
