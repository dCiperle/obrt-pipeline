# obrt-pipeline

## Project

obrt-pipeline is an AI-driven invoicing automation system for Slovenian
sole proprietors and small businesses (obrtniki). The goal is to remove
the manual overhead of monthly invoice preparation, validation, and
submission by orchestrating an agent over the user's existing
accounting tools.

The system integrates with Minimax (accounting platform) and FURS DPR
(the Slovenian tax authority's davčno potrjevanje računov endpoint),
and is driven by a Claude-based agent that interprets free-form input
(notes, voice transcripts, delivery slips) into structured invoice
records.

## Tech stack

Python 3.12, FastAPI, and the Claude Agent SDK. None of this is
wired up yet — the stack will be introduced in Teden 1. Treat the
repository as a documentation-only scaffold at this point.

## Target user

Slovenian obrtniki operating as s.p. or small d.o.o., issuing roughly
8–30 invoices per month. They typically work alone or with one or two
employees, keep books in Minimax, and have limited tolerance for
technical setup.

## Pilot customer

A small Slovenian s.p. in the mechanical and plumbing installation
trade serves as design partner and first pilot customer. All early
design decisions should be validated against the pilot's real workflow
before generalizing.

## Code style

Documentation (README, CONTRIBUTING, CLAUDE.md) and code comments are
written in English. User-facing surface — UI strings, error messages
shown to obrtniki, generated invoice text, sales emails — is written
in Slovenian.

## Where to find things

(To be filled in as the project grows.)
