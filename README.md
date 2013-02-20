GPS Subframe Decoder

by DoYouKnow


Displays telemetry word, handover word, and enables the easy manipulation of various other words in GPS subframe data using a SiRF III GPS such as the PMB-648 available from Parallax for robotics and other applications. GPS subframe data is data that is transmitted directly from the GPS satellites to Earth at a rate of 50 bits per second.

The subframe data that is encoded includes public domain components and classified military components. Some of the fields are not decodable. However, this should display those fields anyway but it is included without any guidance on how to decode those fields, since such information is classified. For example, only the last several bits of the TLM (Telemetry word) relate to any publically known bitfield. The purpose of the rest of the bits is unknown, but since GPS is maintained and was developed by the US military, it is believed they use those bits for their purposes - similar to GPS Precision-codes.

GPS P, or Precision codes are used for military equipment to gain the extra accuracy required from the GPS satellites, such as for certain types of military equipment. C/A, or Coarse Acquisition Codes, are the same type of codes used in car GPS guidance systems. The subframe data is interleaved with the P and C/A codes, but the subframe data does not contain all the data needed to reconstruct a P or C/A code.
