FROM skyscanner:latest

# Compliant
ENV DRONE_TOKEN ""
ENV DRONE_TOKEN "{{ DRONE_TOKEN }}"
ENV DRONE_TOKEN {{ DRONE_TOKEN }}
ENV DRONE_TOKEN {DRONE_TOKEN}
ENV DRONE_TOKEN $DRONE_TOKEN
ENV DRONE_TOKEN=
ENV DRONE_TOKEN="{{ DRONE_TOKEN }}"
ENV DRONE_TOKEN={{ DRONE_TOKEN }}
ENV DRONE_TOKEN={DRONE_TOKEN}
ENV DRONE_TOKEN=$DRONE_TOKEN

# Noncompliant
ENV DRONE_TOKEN YXNkZmZmZmZm_HARDcoded
ENV DRONE_TOKEN=YXNkZmZmZmZm_HARDcoded
ENV DRONE_TOKEN="YXNkZmZmZmZm_HARDcoded"