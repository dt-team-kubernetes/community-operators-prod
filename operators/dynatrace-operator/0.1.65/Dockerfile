FROM scratch

# Core 0.1.65 labels.
LABEL operators.operatorframework.io.bundle.channel.default.v1=alpha
LABEL operators.operatorframework.io.0.1.65.mediatype.v1=registry+v1
LABEL operators.operatorframework.io.0.1.65.manifests.v1=manifests/
LABEL operators.operatorframework.io.0.1.65.metadata.v1=metadata/
LABEL operators.operatorframework.io.0.1.65.package.v1=dynatrace-operator
LABEL operators.operatorframework.io.0.1.65.channels.v1=stable
LABEL operators.operatorframework.io.0.1.65.channel.default.v1=stable
LABEL operators.operatorframework.io.metrics.builder=operator-sdk-v1.36.0
LABEL operators.operatorframework.io.metrics.mediatype.v1=metrics+v1
LABEL operators.operatorframework.io.metrics.project_layout=go.kubebuilder.io/v3

# Copy files to locations specified by labels.
COPY manifests /manifests/
COPY metadata /metadata/
