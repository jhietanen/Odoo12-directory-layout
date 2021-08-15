<img src="https://odoocdn.com/openerp_website/static/src/img/assets/svg/odoo_logo.svg" alt="logo" align="right" height="70"/>

# Odoo Directory Layout
Default directory layout for Odoo 12 deployment

## Layout Structure

    ├── README.md             <- The top-level README for developers using this project.
    ├── bin                   <- Shell scripts. By default, it contains scripts to run test/dev/prod environments.
    ├── conf                  <- Configuration files for test/dev/prod environments.   
    ├── filestore             <- Database attachments and files.
    ├── local                 <- Local addon modules.
    │   └── dummy             <- Empty dummy addon module.
    │   │   └── __init.py__ 
    │   │   └── manifest.py  
    ├── src                   <- Odoo source code.
    ├── env                   <- Virtual environment for the project.

--------

## References
Odoo 12 Documentation: <https://www.odoo.com/documentation/12.0/index.html>

Gajjar, P, Fayolle, A, Brunn, H & Reis, D 2019, *Odoo 12 Development Cookbook - Third Edition*, Packt. 
