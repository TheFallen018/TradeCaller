0.1
  - Initial launch with version numbering

Version 0.1.1
  - Changed convert_to_2_digit to return "None" if no values found
  - Changed get_numbers_in_range to only search selected number types

Version 0.1.2
  - Changed OPTO
  - Changed DET
  - Changed Confirmations

Version 0.1.2 (duplicate entry)
  - Fixed GUI alternate selection not updating config

Version 0.1.3
  - Reworked DET algo

Version 0.2
  - Introduced new GUI
  - GUI includes interactive tables, trading charts, new settings layout
  - Added 4 point tolerance
  - Removed old code and GUI
  - Modified OPTO and DET for 4 point tolerance
  - Added ticks and points as number types
  - Alternates now selectable per algo
  - New config manager

Version 0.2.1
  - Added Pre Opto Algo
  - Added framework for multiple tolerances
  - Added pre-opto interface
  - Added price and date to OPTO

Version 0.2.2
  - Fixed crash from tolerance indexing too high
  - Fixed pre-opto only outputting one type

Version 0.2.3
  - Fixed config issue: ORIGINAL not added
  - Added 240° to pre-opto

Version 0.2.4
  - Added 60° to pre-opto
  - Added price-type search for pre-opto (Search_type_override)

Version 0.2.5
  - Fixed minor output bug in ref time to time

Version 0.2.6
  - Added variable angle framework
  - Added variable angles to pre-opto

Version 0.2.7
  - Fixed min/max price in opto labels being swapped
  - Fixed price and date swap in opto
  - Fixed sidebar bug: 270 entered as 170

Version 0.2.8 — Time spent: 90 mins
  - Added potential price to pre-opto
  - Added min/max range to pre-opto
  - Changed price rounding to 0.1

Version 0.2.9 — Time spent: 45 mins
  - Reverted price rounding change
  - Added DET matching

Version 0.3 — Time spent: 8 hours (2 + 5 + 1)
  - Redesigned DETs (start time and price DET with filtering)
  - New DET interface
  - Added "other data" to Numbers for display in inspector

Version 0.3.1
  - Fixed bug in DET

Version 0.3.2
  - Added pre-opto-det
  - Both algos now called from pre-opto-det
  - Dataframes from both algos are combined

Version 0.3.3
  - Fixed crash in pre_opto_det during dataframe concat
  - pre_opto and DET populate tables via pre_opto_det

Version 0.3.4 — Time with James: 2.5 hours — Total: 7 hours
  - Fixed two-digit conversion to specific range (30 mins)
  - Added up/down range to opto and pre-opto (45 mins)
  - Added time DET to pre-opto (45 mins)
  - Added ticks DET to pre-opto (30 mins)
  - Separated DET and PEP into columns (90 mins)
  - Converted time DETs to numbers (30 mins)

Version 0.3.5 — Time spent: 90 mins
  - Fixed array insertion into dataframe
  - Reformatted Pre-OPTO, DET, OPTO for readability

Version 0.3.6
  - Added minute ranges to Pre-OPTO and GUI
  - Added new config value

Version 0.3.7 — Time: 8 hours (GUI: 7:00–11:00, Discounted 1.5h)
  - Added C1, C2, Y-CH (8:10–11:30, 13:00–15:10)
  - Added CONF GUI
  - Added dataframe output format
  - Script to split multiple branch values into columns

Version 0.3.8
  - Added OD4 for date

Version 0.3.9
  - CONF updates:
    - Two-side alternate matching
    - One side must be original for valid match
    - Fixed Y CH tolerance group
    - Column splitting fixes
    - Converted matching to 2-digit format
    - Added Start Number column

Version 0.3.10
  - 2-digit conversion now applies to entire list

Version 0.3.11
  - Fixed conf2 crash on non-price types

Version 0.3.12 — Time: 2 hours
  - Added reverse option to CONF
  - Fixed CONF bugs
  - Changed price datasheet

Version 0.3.13
  - Fixed bug: all angles removed crashes
  - Set Y_CH to only include angles 0–150
  - Added multithreaded please_wait dialog in CONF GUI

Version 0.3.14
  - Multithreaded CONF algo
  - Multithreaded please_wait for other algos
  - Fixed bugs in pre-opto
  - Split pre-opto-det into separate tables
  - Enabled table sorting by value

Version 0.4.0 — Time: 5 hours (Paid)
  - Added SP_OD
  - Added PEPs along lines
  - SP_OD GUI added
  - Enabled down direction logic
  - Fixed table sorting and data linking
  - Enabled update checking

Version 0.4.1
  - Fixed SP_OD crash on multiple results
  - Fixed Y_CH retaining 240 angle after config reset

Version 0.4.2
  - Fixed negative/high DET issues
  - Added SP to second SP_OD table

Version 0.4.3
  - Fixed "angle off 1" bug by returning empty set

Version 0.4.4
  - Added new datasheets
  - Removed Point, DET, and Ticks number types

Version 0.4.5 — Time taken: 3.5 hours
  - Added BOMB to OPTO

Version 0.5.0 — Time taken: 16 hours
  - Added Radar

Version 0.5.7
  - Fixed issues with val1 alternates in S1_Algos

Version 0.5.8 — 11/03/25–12/03/25 — Time: 9 hours (2h on 11th, 7h on 12th)
  - GUI line selection improvements
  - Fixed tooltip location
  - Fixed line clearing on update
  - Added pop-out window option
  - Switched text toggle from checkbox (for spacing and angle columns)
  - Added dashed lines when selected
  - Added select/clear line options
  - Miscellaneous GUI fixes

Version 0.5.9 - 12/03/25 - 1.5 hours
  Time on call: 30 mins
  - Fixed: P value not updating
  - Fixed: T value not drawing lines
  - Removed numbers in left table when clearing lines
  - Removed highlights on clear

Version 0.5.10 - 14/03/25 to 25/03/25 - 22 hours
  14/03/25 - 4 hours
    - Implemented placeholder GUI for swings
    - Method to draw lines from separate tab
    - Method to draw lines without knowing Square of 9s viewer position
  14/03/25 - 4 hours (continued)
    - Call with James: 3 hours
    - Started swing algo
    - Implemented date wrapping from 1200–100 (skipped 1300s)
    - Added 0°, 90°, 180°, 270° angles for local swing 1
  16/03/25 - 3 hours
    - Call with James: 2 hours
    - Implemented valid date check from date list: 1 hour
  18/03/25 - 3 hours
    - Started implementing alternate dates
  19/03/25 - 4 hours
    - Continued alternate date logic
  20/03/25 - 4 hours
    - Implemented alternate dates
  23/03/25 - 1 hour
    - Finished alternate dates
  24/03/25 - 5.5 hours
    - Alternate dates completed: 2 hours
    - Call with James: 1.5 hours
    - Changed DET algo to run on matched dates: 1 hour
    - Fixed multiple line issue in GUI: 1 hour
  25/03/25 - 6 hours
    - Reorganised algo outputs for display: 1 hour
    - Created mutable dict for Number to list[Number]: 30 mins
    - Enabled swings runnable from GUI: 1.5 hours
    - Created output table for GUI: 2 hours
    - Rebuilt .exe compilation process: 1 hour

Version 0.5.11 - 26/03/25 - 1 hour
  - Redesigned for light theme compatibility

Version 0.5.12 - 26/03/25 - 1.5 hours
  - Bug fixes with James: 1 hour
  - Fixed range issue in swings: 30 mins

Version 0.5.13 - 26/03/25 - 1.5 hours
  - Re-added alternates to get_valid_dates
  - Added post-algo filtering for get_valid_dates
  - Implemented basic debug display in table

Version 0.5.14 - 27/03/25 - 3 hours
  - Added buttons for LS1, LS2, MS1, MS2
  - Logic to populate swings from buttons and selected lines
  - Optional 120° and 240° angles for swings
  - Implemented table appending

Version 0.5.15 - 01/04/25 and 02/04/25 - 5.5 hours
  01/04/25 - 3.5 hours
    - Selectable 90°, 120°, and custom angles in swings: 1 hour
    - Default angle key for undefined symbols: 1 hour
    - Call with James: 1.5 hours
Version 0.5.16 - 02/04/25 - 09/04/23 - 28.5 hours
  02/04/25 - 6.5 hours
    - Refactored code to support type checking
    - Added operator definitions to Number class
    - Created "get_valid_dates" method for Swings
    - Created "convert_prices_to_DETs" method for Swings
    - Call with James: 2 hours
  03-06/04/25 - 6 hours
    - Implemented multiple DET start date checks
    - Fixed bug with DETs being incorrectly interpreted as dates
    - Call with James: 1.5 hours
  07/04/25 - 6 hours
    - Implemented binary search for matching: 2.5 hours
    - Call with James: 1.5 hours
    - Started implementing binary search for price matching: 2 hours
  08/04/25 - 4 hours
    - Implemented binary search for price and date swings algos: 2 hours
    - Call with James: 2 hours
  09/04/25 - 8 hours
    - Implemented GUI events for price swings algo: 2 hours
    - Implemented formatting of outputs into tabular form: 3 hours
    - Tied both together and tested GUI: 1 hour
    - Call with James: 2 hours
Version 0.6.0
  10/04/25 - 11/04/25 - 5.5 hours
    - Implemented O_Det GUI: 3 hours
    - Implemented O_Det output formatting: 1 hour
    - Fixed RADAR bugs: 1 hour
    - Bug fixes in O_Det: 30 mins

