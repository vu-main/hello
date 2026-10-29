# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

A static, dependency-free HTML page: a name heading plus a numbered list of three learning goals. There is no build system, package manager, linter, or test suite — and no git repository yet.

## Running

Open `index.html` directly in a browser (no server needed).

## Structure

- `index.html` — page content; links `style.css` via a relative `<link>`, so both files must stay in the same directory.
- `style.css` — all styling (centered 600px `main` column, element selectors only, no classes/IDs).

The page content is in Russian (`<html lang="ru">`); keep new text consistent with that.
