FROM hysds/pge-base:develop-es1

MAINTAINER jlinick "Justin.P.Linick@jpl.nasa.gov"
LABEL description="Standard Completeness Evaluator"

USER ops

COPY . /home/ops/verdi/ops/standard_product_completeness_evaluator

WORKDIR /home/ops
CMD ["/bin/bash", "--login"]
