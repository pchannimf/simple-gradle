FROM public.ecr.aws/lambda/java:11.2022.02.01.10
COPY build/classes/java/main ${LAMBDA_TASK_ROOT}
COPY build/classes/kotlin/main ${LAMBDA_TASK_ROOT}
COPY build/resources/main ${LAMBDA_TASK_ROOT}
COPY build/dependency/* ${LAMBDA_TASK_ROOT}/lib/
