<p align="center">

<h1 align="center"><img src="data/favicon.png" width="30px" alt="Icon" title="Icon">FluidServer</h1>

<p align="center">
<img src="https://img.shields.io/badge/license-MIT-green" alt="License" title="License" >
<img src="https://img.shields.io/badge/license-Apache-blue" alt="License" title="License" >
</p>

</p>

> Open source scalable POS-system server

Is it just me or are most commercial POS-systems garbage? Want something better in life? Something made to be good? Try FluidServer!

FluidServer is a scalable POS-system server for - well - people who don't hate themselves. It makes it easier for system administrators and developer to use and implement - it's also more scalable than most POS-system servers.
###### [Wait, what the hell?](https://gist.github.com/fgclue/67781ee2f4d3a218d8ca22e4e1024bc5)

# Usage Example

Sending a request to `/api/product/1` will return the product data in this format:
`Name|Price|Type (UN/KG)|Controlled (for pharmacies)`.

If you want to host in a port different than the default `1618`, just run FluidServer with the argument `--port` or `-p` and your port. However, using ports below 1024 are not recommended as those ports are considered "privileged ports" and require root to use.

# Integration
If you are a developer of a POS-system then you can easily integrate FluidServer by reading the [documentation](https://docs.fluidserver.biitle.nl).

Also, you can use Swagger UI to test the APIs from your browser (while running FluidServer of course.)

Python 3.12+ is required to use FluidServer.

# Meta
Built by clue <<lost@biitle.nl>>.

Distributed under the MIT license.

# Contributing
1. Fork the repo (https://github.com/FluidServer/server)
2. Create your feature branch (`git checkout -b feature/yournewfeature`)
3. Commit your changes (`git commit -am 'Add some change'`)
4. Push to the branch (`git push origin feature/yournewfeature`)
5. Create a new pull request

`SPDX-License-Identifier: MIT or Apache-2.0`