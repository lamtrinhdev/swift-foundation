##===----------------------------------------------------------------------===##
##
## This source file is part of the Swift open source project
##
## Copyright (c) 2024 Apple Inc. and the Swift project authors
## Licensed under Apache License v2.0
##
## See LICENSE.txt for license information
## See CONTRIBUTORS.md for the list of Swift project authors
##
## SPDX-License-Identifier: Apache-2.0
##
##===----------------------------------------------------------------------===##

target_sources(FoundationEssentials PRIVATE
    BinaryInteger+NumericStringRepresentation.swift
    Date+ISO8601FormatStyle.swift
    DateComponents+ISO8601FormatStyle.swift
    DiscreteFormatStyle.swift
    FormatParsingUtilities.swift
    FormatStyle.swift
    FormatterCache.swift
    ParseStrategy.swift
    ParseableFormatStyle.swift)
