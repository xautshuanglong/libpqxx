# ##############################################################################
# AUTOMATICALLY GENERATED FILE -- DO NOT EDIT.
#
# This file is generated automatically by libpqxx's template2mak.py script, and
# will be rewritten from time to time.
#
# If you modify this file, chances are your modifications will be lost.
#
# The template2mak.py script should be available in the tools directory of the
# libpqxx source archive.
#
# Generated from template './include/CMakeLists.txt.template'.
# ##############################################################################
install(
    DIRECTORY pqxx "${PROJECT_BINARY_DIR}/include/pqxx"
    DESTINATION ${CMAKE_INSTALL_INCLUDEDIR}
    FILES_MATCHING
    PATTERN array.hxx
    PATTERN array
    PATTERN binarystring.hxx
    PATTERN binarystring
    PATTERN compiler-public.hxx
    PATTERN compiler-public
    PATTERN connection.hxx
    PATTERN connection
    PATTERN cursor.hxx
    PATTERN cursor
    PATTERN dbtransaction.hxx
    PATTERN dbtransaction
    PATTERN errorhandler.hxx
    PATTERN errorhandler
    PATTERN except.hxx
    PATTERN except
    PATTERN field.hxx
    PATTERN field
    PATTERN isolation.hxx
    PATTERN isolation
    PATTERN largeobject.hxx
    PATTERN largeobject
    PATTERN nontransaction.hxx
    PATTERN nontransaction
    PATTERN notification.hxx
    PATTERN notification
    PATTERN pipeline.hxx
    PATTERN pipeline
    PATTERN prepared_statement.hxx
    PATTERN prepared_statement
    PATTERN result.hxx
    PATTERN result
    PATTERN result_iterator.hxx
    PATTERN result_iterator
    PATTERN robusttransaction.hxx
    PATTERN robusttransaction
    PATTERN row.hxx
    PATTERN row
    PATTERN separated_list.hxx
    PATTERN separated_list
    PATTERN strconv.hxx
    PATTERN strconv
    PATTERN stream_from.hxx
    PATTERN stream_from
    PATTERN stream_to.hxx
    PATTERN stream_to
    PATTERN subtransaction.hxx
    PATTERN subtransaction
    PATTERN transaction.hxx
    PATTERN transaction
    PATTERN transaction_base.hxx
    PATTERN transaction_base
    PATTERN transactor.hxx
    PATTERN transactor
    PATTERN types.hxx
    PATTERN types
    PATTERN util.hxx
    PATTERN util
    PATTERN version.hxx
    PATTERN version
    PATTERN zview.hxx
    PATTERN zview
    PATTERN internal/callgate.hxx
    PATTERN internal/compiler-internal-post.hxx
    PATTERN internal/compiler-internal-pre.hxx
    PATTERN internal/conversions.hxx
    PATTERN internal/encoding_group.hxx
    PATTERN internal/encodings.hxx
    PATTERN internal/ignore-deprecated-post.hxx
    PATTERN internal/ignore-deprecated-pre.hxx
    PATTERN internal/libpq-forward.hxx
    PATTERN internal/sql_cursor.hxx
    PATTERN internal/statement_parameters.hxx
    PATTERN internal/gates/connection-errorhandler.hxx
    PATTERN internal/gates/connection-largeobject.hxx
    PATTERN internal/gates/connection-notification_receiver.hxx
    PATTERN internal/gates/connection-pipeline.hxx
    PATTERN internal/gates/connection-sql_cursor.hxx
    PATTERN internal/gates/connection-stream_from.hxx
    PATTERN internal/gates/connection-stream_to.hxx
    PATTERN internal/gates/connection-transaction.hxx
    PATTERN internal/gates/errorhandler-connection.hxx
    PATTERN internal/gates/icursor_iterator-icursorstream.hxx
    PATTERN internal/gates/icursorstream-icursor_iterator.hxx
    PATTERN internal/gates/result-connection.hxx
    PATTERN internal/gates/result-creation.hxx
    PATTERN internal/gates/result-pipeline.hxx
    PATTERN internal/gates/result-sql_cursor.hxx
    PATTERN internal/gates/transaction-sql_cursor.hxx
    PATTERN internal/gates/transaction-transactionfocus.hxx
    PATTERN config-public-compiler.h
    PATTERN pqxx
    PATTERN doc EXCLUDE
)

install(
    DIRECTORY pqxx/doc/
    DESTINATION ${CMAKE_INSTALL_DOCDIR}
    FILES_MATCHING
    PATTERN accessing-results.md
    PATTERN datatypes.md
    PATTERN escaping.md
    PATTERN getting-started.md
    PATTERN mainpage.md
    PATTERN performance.md
    PATTERN prepared-statement.md
    PATTERN streams.md
    PATTERN thread-safety.md
)
