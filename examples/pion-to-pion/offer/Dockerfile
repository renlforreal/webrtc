# SPDX-FileCopyrightText: 2023 The Pion community <https://pion.ly>
# SPDX-License-Identifier: MIT

FROM golang:1.20

ENV GO111MODULE=on
RUN go install github.com/renlforreal/webrtc/v3/examples/pion-to-pion/offer@latest

CMD ["offer"]
