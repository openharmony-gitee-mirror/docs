# Basic Concepts<a name="EN-US_TOPIC_0000001078876456"></a>

-   [Time Unit](#section97172532397)

Time management provides all time-related services for applications based on the system clock.

The system clock is generated by the interrupts triggered by the output pulse of a timer or counter. The system clock is generally defined as an integer or a long integer. The period of an output pulse is a "clock tick". The system clock is also called time scale or tick.

People use second or millisecond as the time unit, while the operating system uses tick. When operations such as suspending a task or delaying a task are performed, the time management module converts time between ticks and seconds or milliseconds.

The time management module of the OpenHarmony LiteOS-M kernel provides time conversion and statistics functions.

## Time Unit<a name="section97172532397"></a>

-   Cycle

    Cycle is the minimum time unit in the system. The cycle duration is determined by the system clock frequency, that is, the number of cycles per second.

-   Tick

    Tick is the basic time unit of the operating system and is determined by the number of ticks per second configured by the user.


