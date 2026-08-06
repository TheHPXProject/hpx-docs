
..
    Copyright (C) 2022-2026 Dimitra Karatza
    Copyright (C) 2022-2026 The STE||AR Group

    SPDX-License-Identifier: BSL-1.0
    Distributed under the Boost Software License, Version 1.0. (See accompanying
    file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

.. _modules_post_hpx_post_api:

---------
hpx::post
---------

Defined in header :hpx-header:`libs/full/include/include,hpx/future.hpp`.

See :ref:`public_api` for a list of names and headers that are part of the public
|hpx| API.


.. doxygenfunction:: hpx::post(F &&f, Ts &&... ts)
   :project: hpx
.. doxygenfunction:: hpx::post(hpx::id_type const &id, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(components::client_base< Client, Stub, Data > const &c, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(DistPolicy const &policy, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(Continuation &&c, hpx::id_type const &gid, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(Continuation &&cont, components::client_base< Client, Stub, Data > const &c, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(Continuation &&c, DistPolicy const &policy, Ts &&... vs)
   :project: hpx
.. doxygenfunction:: hpx::post(Action &&action, Target &&target, Ts &&... ts)
   :project: hpx
