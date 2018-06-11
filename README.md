# Qbus-Interface-Design
Circuit designs for interfacing to the legacy DEC Qbus for Slave and Master/Slave implementations.

Background

Digital Equipment Corporation (DEC) developed and openly published the "LSI-11 Bus" specification in 1979 specifically to address interface costs for the upcoming range of PDP-11 16-bit minicomputers. Most often referred to as the Qbus, it reduced the interface logic requirements of the flagship bus of the time, the Unibus, mostly by multiplexing the Address and Data signalling functions on the same bus lines. This was highly successful and the Qbus continued to be viable through the release of the PDP-11/93 in 1990.

Project Justification

Through various on-line resources dedicated to preserving the history of computer development, many people worldwide practice the hobby of "Vintage Computing" or "Retro Computing". A huge part of the hobby is keeping the legacy computers alive and sharing vital information with others of similar interests. Unfortunately, it is becoming more difficult and expensive to obtain the actual hardware in proper working order. Therefore, many creative hobbyists endeavor to functionally re-create the hardware using more modern technology. This project is dedicated to supporting those interested in doing this by providing an Open Source/Open Hardware set of circuit functions supporting the Qbus.

Project Guidelines

    Create Open Source and Open Hardware compliant under a non-restrictive license
    Standardize on KiCad for schematic and layout as the tool suite is totally open, free, very capable and community supported
    Write an initial design specification, evolving as the project issues are resolved and ultimately finalized
    Create layout templates for Dual and Quad Qbus form factors
    Address the issue of obsolete bus interface logic with a workable compromise using long-term available devices
    If needed, programmable logic (CPLD or FPGA) designs must be generic and independent of a particular vendor architecture
    Also, any PLD tools used must be available under a free license for individuals, hobbyists, etc.
    Take advantage of group buys for circuit boards and component
    
