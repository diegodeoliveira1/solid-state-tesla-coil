# Construction challenges and engineering lessons

## 1. Copper winding

The team had to wind copper wire around the **primary and secondary coils**. The long, tightly spaced **secondary winding** was especially difficult to complete consistently without damaging or disturbing the wire.

**Lesson:** Physical workmanship is part of the electrical design. Coil geometry, handling, and repeatability matter to a resonant system.

## 2. Electrical connections to copper wire

Connecting the wound copper wire to other conductors through solder joints was challenging. The team had to pay attention to the connection between winding wire and the rest of the circuit, as well as the mechanical integrity of the joints.

**Lesson:** A mechanically weak or electrically intermittent connection can prevent a circuit from functioning as expected; construction quality cannot be separated from electrical performance.

## 3. Correct primary-coil connection

Connecting the primary winding as intended was another important troubleshooting concern. The coil's electrical connections determine how primary current is switched and how energy is coupled magnetically into the secondary.

**Lesson:** In a multi-stage electronics prototype, correctly integrated subsystems matter as much as the choice of individual components.

## 4. MOSFET stress and failure

Protecting the IRFP460 was a known concern. The team included gate-related and drain-source transient-suppression components, and a resistive ballast to reduce the available input current. A **separate recorded test ended in a reported MOSFET failure**.

Potential failure mechanisms include overvoltage during switching, excessive current, overheating, and unintended switching. **These are hypotheses only; there are no measurements that isolate a root cause.**

**Lesson:** Protective parts and nominal component ratings do not replace actual measurement of switching and thermal conditions.

## 5. Maintaining hand-soldered joints

The electronics were assembled using a collection of wired and soldered connections. Maintaining electrical continuity during handling and testing was an ongoing concern.

**Lesson:** Point-to-point prototypes benefit from systematic connection checks, careful documentation, and mechanical support for conductors.

## Engineering perspective

The goal was to build a device that could demonstrate a discharge; success required both electronics understanding and hands-on construction. The documented MOSFET failure underscores the difference between a **successful demonstration** and a **reliable, characterized design**.

> **Safety:** This is an account of completed work, not a guide for building or modifying a mains-powered Tesla coil. Additional experiments require qualified laboratory oversight and an independently reviewed safe design.
