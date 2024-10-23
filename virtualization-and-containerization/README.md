<h1>
  <span class="headline">Intro to Cloud Infrastructure</span>
  <span class="subhead">Virtualization and Containerization</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to describe the roles of virtualization and containerization in cloud infrastructure.



## How Does Cloud Infrastructure Work?

The capabilities of cloud infrastructure are enabled by two key concepts:

- **Virtualization:** This technology lets you run several virtual machines (VMs) on one physical server, making better use of resources and improving efficiency.

- **Containerization:** This method wraps applications and everything they need into small, isolated packages called containers, allowing them to run reliably in different environments.

These technologies work together to make cloud services flexible, scalable, and cost-effective.

<br>

![Virtual Machines vs. Containers](./assets/vms-vs-containers.png)

[Source](https://www.docker.com/what-container#/package_software)

## Virtualization

**Virtualization** divides physical computing resources, making cloud computing possible.

Using software called a **hypervisor**, virtualization splits the physical resources of a server (such as RAM, CPU, and storage) into virtual resources. For example, you may be using this technology right now to run a virtual machine on your laptop.

A physical server running a hypervisor is called a **host**.

**Virtual machines** (VMs), or **guests**, run on this host. The virtual machine operates like a real server, with access to virtual hardware, but it’s unaware that it's running on shared resources rather than a physical server.

## Containerization

How is containerization different from virtualization?

A **container** is a form of virtualization at the **operating system** level. The OS kernel creates isolated environments for running specific applications.

Instead of dividing physical resources, tools like Docker split **OS resources**—such as the process namespace, network, storage, and file system. Each container has its own processes and file system, making it much lighter and faster than a virtual machine.

<div class="activity knowledge-check">
  <h2 class="title">What is the biggest difference between virtualization and containerization?</h2>
  <span class="minutes">2 min</span>
</div>

<details>
<summary>✅ Click to see our answer</summary>
<br>

<p> In a <strong>virtualized</strong> environment, each virtual machine has its own guest OS.<p>
<p> In a <strong>containerized</strong> environment, the operating system lives on the physical server and the OS resources are split across each container.<p>

</details>
