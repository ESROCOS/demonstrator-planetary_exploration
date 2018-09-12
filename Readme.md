# Planetary Exploration Demonstrator

# Architecture
![Image of PED Architecture](images/architecture.png)

# Taste Interface

![Image of PED Interaface View](images/interfaceview.png)

# Issues

In any case there is a GR740 communicating with a x86 partition, all involved interface parameters have to be encoded using **UPER**.
Otherwise there will be endianess and conversion issues.
