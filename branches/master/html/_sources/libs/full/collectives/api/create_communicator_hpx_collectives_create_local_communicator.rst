
..
    Copyright (C) 2022-2026 Dimitra Karatza
    Copyright (C) 2022-2026 The STE||AR Group

    SPDX-License-Identifier: BSL-1.0
    Distributed under the Boost Software License, Version 1.0. (See accompanying
    file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

.. _modules_create_communicator_hpx_collectives_create_local_communicator_api:

-------------------------------------------
hpx::collectives::create_local_communicator
-------------------------------------------

Defined in header hpx/collectives.hpp.

See :ref:`public_api` for a list of names and headers that are part of the public
|hpx| API.


See also:

   - :ref:`hpx::collectives::communicator <modules_create_communicator_hpx_collectives_communicator_api>`
   - :ref:`hpx::collectives::create_communicator <modules_create_communicator_hpx_collectives_create_communicator_api>`
   - :ref:`hpx::collectives::create_hierarchical_communicator <modules_create_communicator_hpx_collectives_create_hierarchical_communicator_api>`
   - :ref:`hpx::collectives::communicator::set_info <modules_create_communicator_hpx_collectives_communicator_set_info_api>`
   - :ref:`hpx::collectives::communicator::get_info <modules_create_communicator_hpx_collectives_communicator_get_info_api>`
   - :ref:`hpx::collectives::communicator::is_root <modules_create_communicator_hpx_collectives_communicator_is_root_api>`

.. doxygenfunction:: hpx::collectives::create_local_communicator(char const *basename, num_sites_arg num_sites, this_site_arg this_site, generation_arg generation=generation_arg(), root_site_arg root_site=root_site_arg())
   :project: hpx
.. doxygenfunction:: hpx::collectives::create_local_communicator(hpx::launch::sync_policy policy, char const *basename, num_sites_arg num_sites, this_site_arg this_site, generation_arg generation, root_site_arg root_site)
   :project: hpx
