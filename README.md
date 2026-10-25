# Ballah League Fantasy Basketball Analytics

## Overview
A private, non-commercial fantasy basketball analytics project for Ballah League, a nine-team Yahoo Fantasy Basketball league using nine-category Rotisserie scoring.

The project is being developed for personal use by one league manager during the 2026–27 NBA season.

## Purpose
The application will support data-driven roster management and championship optimisation, including:

- Tracking league standings and category statistics
- Comparing actual results against rest-of-season projections
- Evaluating free-agent additions, drops and trades
- Analysing player performance and injury-related changes
- Monitoring roster game limits
- Modelling final Rotisserie standings and championship probabilities

## Yahoo Fantasy Sports Data Required
The application will request read-only access to:

- League settings and standings
- Team rosters and team statistics
- Player statistics and positional eligibility
- Available free agents and waiver information
- League transactions, including trades, additions and drops

## Technical Architecture
The intended integration uses Yahoo Fantasy Sports API authorisation, Google Apps Script and a private Google Sheet. The integration is designed to refresh approximately once daily and maintain historical snapshots for analysis.

## Access and Privacy
This is a single-user, single-league, non-commercial project. It is not a public application or subscription service. No Yahoo account passwords, API secrets, access tokens, or private league datasets will be committed to this public repository. No write access to Yahoo Fantasy Sports is requested.

## Development Status
Planning and API access application stage. Implementation is subject to Yahoo approval.
