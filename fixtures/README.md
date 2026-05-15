# Conformance Fixtures

This directory contains protocol-level JSON fixtures for SDK and implementation conformance tests.

- `valid/`: messages that must validate against `schema/event-emission-0.1.0.schema.json`.
- `invalid/`: messages that must fail validation against `schema/event-emission-0.1.0.schema.json`.

SDK repositories should consume these fixtures as protocol test vectors instead of redefining their own baseline examples.
