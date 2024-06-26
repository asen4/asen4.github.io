---
layout: page
title: mdadm Linear Device
description: mdadm Library for Linear Devices
img: assets/img/linux.png
importance: 9
category: work
---

<div>

    <p>In Linux, mdadm (Multiple Disk and Device Management) is a utility used to manage software RAID (Redundant Array of Independent Disks) devices, which combines multiple physical disks into a single logical device to increase performance and reliability. Over the course of a few months, I worked on developing a linear device—a Non-RAID configuration that concatenates the disks like a normal RAID configuration but without the performance increase and redundancy. To clarify, not having redundancy means that if one disk fails, the data on that disk may be lost.</p>

    <p>This mdadm library allows users to work with the linear device with ease. Users may mount the linear device to read or write into disks or blocks and unmount the device once they finish. Furthermore, caching was implemented to improve latency and reduce overall cost. Networking was also added to provide greater flexibility and give users the ability to connect to and interact with remote servers.</p>

    <p>I learned how to...</p>
    <ul>
        <li>Write a program using the C programming language.</li>
        <li>Fix segmentation faults and other memory-related errors.</li>
        <li>Gain experience using a debugger (i.e., gdb).</li>
        <li>Code functionalities of the cache.</li>
        <li>Program a client that connects to a server and can send/receive packets.</li>
    </ul>

</div>
