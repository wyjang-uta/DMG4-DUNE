#
cmake_minimum_required(VERSION 3.11)

# Project info.
project(
  DMG4-DUNE
  VERSION 0.1
  DESCRIPTION "DMG4 application under 120 GeV proton beam (DUNE-like) setup"
  LANGUAGES CXX)

add_executable(dmg4_dune dmg4_dune.cc)
