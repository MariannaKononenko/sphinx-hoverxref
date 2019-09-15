Configuration
=============

The default settings should be enough for most of the cases.
For more specific use cases, you can customize these configuration options in your ``conf.py`` file:

.. confval:: hoverxref_project (string)

   Read the Docs project slug

   Default: The value of the ``READTHEDOCS_PROJECT`` environment variable

.. confval:: hoverxref_version (string)

   Read the Docs version slug

   Default: The value ``READTHEDOCS_VERSION`` environment variable

.. confval:: hoverxref_tooltip_api_host (string)

   Host URL for the API to retrieve the tooltip content

   Default: ``https://readthedocs.org``

.. confval:: hoverxref_auto_ref (bool)

   Make all ``:ref:`` role to show a tooltip

   Default: ``False``

.. confval:: hoverxref_domains

   Description: List containing the Sphinx Domain's names where ``hoverxref`` has to be applied.

   .. warning::

      Only Python Domain (``py``) is currently supported.

   Default: ``[]``

   Type: list

.. confval:: hoverxref_roles

   Description: List containing roles where ``hoverxref`` has to be applied.

   Default: ``[]``

   Type: list

.. confval:: hoverxref_tooltip_class

   Description: CSS class to add to ``div`` created for the tooltip

   Default: ``rst-content``

   Type: string

.. confval:: hoverxref_sphinxtabs

   Description: trigger an extra step to render tooltips where its content has a `Sphinx Tabs`_

   Default: ``False``

   Type: bool

.. _Sphinx Tabs: https://github.com/djungelorm/sphinx-tabs

.. confval:: hoverxref_mathjax

   Description: trigger an extra step to render tooltips where its content has a `Mathjax`_

   Default: ``False``

   Type: bool

.. _Mathjax: http://www.sphinx-doc.org/es/master/usage/extensions/math.html#module-sphinx.ext.mathjax

.. warning::

   The following settings are passed directly to Tooltipster_. See https://iamceege.github.io/tooltipster/#options for more information about their descriptions.

.. confval:: hoverxref_tooltip_theme

   Default: ``['tooltipster-shadow', 'tooltipster-shadow-custom']``

   Type: list of strings

.. confval:: hoverxref_tooltip_interactive

   Default: ``True``

   Type: bool

.. confval:: hoverxref_tooltip_maxwith

   Default: ``450``

   Type: int

.. confval:: hoverxref_tooltip_side

   Default: ``right``

   Type: string

.. confval:: hoverxref_tooltip_animation

   Default: ``fade``

   Type: string

.. confval:: hoverxref_tooltip_animation_duration

   Default: ``0``

   Type: int

.. confval:: hoverxref_tooltip_content

   Default: ``Loading...``

   Type: string

.. _Tooltipster: https://iamceege.github.io/tooltipster/
