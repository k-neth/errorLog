Microsoft Windows [Version 10.0.19044.3570]
(c) Microsoft Corporation. All rights reserved.

C:\Users\KenKen>pip install matplotlib
Collecting matplotlib
  Using cached matplotlib-3.8.0.tar.gz (35.9 MB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Collecting contourpy>=1.0.1 (from matplotlib)
  Obtaining dependency information for contourpy>=1.0.1 from https://files.pythonhosted.org/packages/b4/d9/42680a17d43edda04ab2b3f11125cf97b61bce5d3b52721a42960bf748bd/contourpy-1.1.1-cp310-cp310-win32.whl.metadata
  Using cached contourpy-1.1.1-cp310-cp310-win32.whl.metadata (5.9 kB)
Requirement already satisfied: cycler>=0.10 in c:\users\kenken\appdata\local\programs\python\python310-32\lib\site-packages (from matplotlib) (0.12.1)
Collecting fonttools>=4.22.0 (from matplotlib)
  Obtaining dependency information for fonttools>=4.22.0 from https://files.pythonhosted.org/packages/4e/97/22751b5461ed64c6531754f7d7d42d7146694671ce8d085c21c34ca79386/fonttools-4.43.1-cp310-cp310-win32.whl.metadata
  Using cached fonttools-4.43.1-cp310-cp310-win32.whl.metadata (155 kB)
Collecting kiwisolver>=1.0.1 (from matplotlib)
  Obtaining dependency information for kiwisolver>=1.0.1 from https://files.pythonhosted.org/packages/70/d1/5ab93ee00ca5af708929cc12fbe665b6f1ed4ad58088e70dc00e87e0d107/kiwisolver-1.4.5-cp310-cp310-win32.whl.metadata
  Using cached kiwisolver-1.4.5-cp310-cp310-win32.whl.metadata (6.5 kB)
Requirement already satisfied: numpy<2,>=1.21 in c:\users\kenken\appdata\local\programs\python\python310-32\lib\site-packages (from matplotlib) (1.26.1)
Requirement already satisfied: packaging>=20.0 in c:\users\kenken\appdata\local\programs\python\python310-32\lib\site-packages (from matplotlib) (23.2)
Collecting pillow>=6.2.0 (from matplotlib)
  Using cached Pillow-10.1.0.tar.gz (50.8 MB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: pyparsing>=2.3.1 in c:\users\kenken\appdata\local\programs\python\python310-32\lib\site-packages (from matplotlib) (3.1.1)
Collecting python-dateutil>=2.7 (from matplotlib)
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting six>=1.5 (from python-dateutil>=2.7->matplotlib)
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Using cached contourpy-1.1.1-cp310-cp310-win32.whl (399 kB)
Using cached fonttools-4.43.1-cp310-cp310-win32.whl (2.1 MB)
Using cached kiwisolver-1.4.5-cp310-cp310-win32.whl (46 kB)
Building wheels for collected packages: matplotlib, pillow
  Building wheel for matplotlib (pyproject.toml) ... error
  error: subprocess-exited-with-error

  × Building wheel for matplotlib (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [792 lines of output]
      WARNING setuptools_scm.pyproject_reading toml section missing 'pyproject.toml does not contain a tool.setuptools_scm section'
      C:\Users\KenKen\AppData\Local\Temp\pip-build-env-nxsir_rj\overlay\Lib\site-packages\setuptools_scm\git.py:308: UserWarning: git archive did not support describe output
        warnings.warn("git archive did not support describe output")
      C:\Users\KenKen\AppData\Local\Temp\pip-build-env-nxsir_rj\overlay\Lib\site-packages\setuptools_scm\git.py:327: UserWarning: unprocessed git archival found (no export subst applied)
        warnings.warn("unprocessed git archival found (no export subst applied)")

      Edit mplsetup.cfg to change the build options; suppress output with --quiet.

      BUILDING MATPLOTLIB
            python: yes [3.10.7 (tags/v3.10.7:6cc6b13, Sep  5 2022, 13:51:36) [MSC
                        v.1933 32 bit (Intel)]]
          platform: yes [win32]
             tests: no  [skipping due to configuration]
            macosx: no  [Mac OS-X only]

      running bdist_wheel
      running build
      running build_py
      creating build
      creating build\lib.win32-cpython-310
      copying lib\pylab.py -> build\lib.win32-cpython-310
      creating build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\animation.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\artist.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\axis.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_bases.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_managers.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_tools.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\bezier.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\category.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\cbook.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\cm.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\collections.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\colorbar.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\colors.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\container.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\contour.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\dates.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\dviread.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\figure.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\font_manager.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\gridspec.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\hatch.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\image.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\layout_engine.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\legend.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\legend_handler.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\lines.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\markers.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\mathtext.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\mlab.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\offsetbox.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\patches.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\path.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\patheffects.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\pylab.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\pyplot.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\quiver.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\rcsetup.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\sankey.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\scale.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\spines.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\stackplot.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\streamplot.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\table.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\texmanager.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\text.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\textpath.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\ticker.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\transforms.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\typing.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\units.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\widgets.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_afm.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_animation_data.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_blocking_input.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_cm.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_cm_listed.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_color_data.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_constrained_layout.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_docstring.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_enums.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_fontconfig_pattern.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_internal_utils.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_layoutgrid.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_mathtext.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_mathtext_data.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_pylab_helpers.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_text_helpers.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_tight_bbox.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_tight_layout.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_type1font.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_version.py -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\__init__.py -> build\lib.win32-cpython-310\matplotlib
      creating build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\_axes.py -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\_base.py -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\_secondary_axes.py -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\__init__.py -> build\lib.win32-cpython-310\matplotlib\axes
      creating build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_agg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_cairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk3.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk3agg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk3cairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk4.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk4agg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_gtk4cairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_macosx.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_mixed.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_nbagg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_pdf.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_pgf.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_ps.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qt.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qt5.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qt5agg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qt5cairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qtagg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_qtcairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_svg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_template.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_tkagg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_tkcairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_webagg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_webagg_core.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_wx.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_wxagg.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\backend_wxcairo.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\qt_compat.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\_backend_gtk.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\_backend_pdf_ps.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\_backend_tk.py -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\__init__.py -> build\lib.win32-cpython-310\matplotlib\backends
      creating build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\projections\geo.py -> build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\projections\polar.py -> build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\projections\__init__.py -> build\lib.win32-cpython-310\matplotlib\projections
      creating build\lib.win32-cpython-310\matplotlib\sphinxext
      copying lib\matplotlib\sphinxext\figmpl_directive.py -> build\lib.win32-cpython-310\matplotlib\sphinxext
      copying lib\matplotlib\sphinxext\mathmpl.py -> build\lib.win32-cpython-310\matplotlib\sphinxext
      copying lib\matplotlib\sphinxext\plot_directive.py -> build\lib.win32-cpython-310\matplotlib\sphinxext
      copying lib\matplotlib\sphinxext\__init__.py -> build\lib.win32-cpython-310\matplotlib\sphinxext
      creating build\lib.win32-cpython-310\matplotlib\style
      copying lib\matplotlib\style\core.py -> build\lib.win32-cpython-310\matplotlib\style
      copying lib\matplotlib\style\__init__.py -> build\lib.win32-cpython-310\matplotlib\style
      creating build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\compare.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\conftest.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\decorators.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\exceptions.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\widgets.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\_markers.py -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\__init__.py -> build\lib.win32-cpython-310\matplotlib\testing
      creating build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\conftest.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_afm.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_agg.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_agg_filter.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_animation.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_api.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_arrow_patches.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_artist.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_axes.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_axis.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backends_interactive.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_bases.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_cairo.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_gtk3.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_macosx.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_nbagg.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_pdf.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_pgf.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_ps.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_qt.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_svg.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_template.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_tk.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_tools.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_backend_webagg.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_basic.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_bbox_tight.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_category.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_cbook.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_collections.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_colorbar.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_colors.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_compare_images.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_constrainedlayout.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_container.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_contour.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_cycles.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_dates.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_determinism.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_doc.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_dviread.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_figure.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_fontconfig_pattern.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_font_manager.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_ft2font.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_getattr.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_gridspec.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_image.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_legend.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_lines.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_marker.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_mathtext.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_matplotlib.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_mlab.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_offsetbox.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_patches.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_path.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_patheffects.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_pickle.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_png.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_polar.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_preprocess_data.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_pyplot.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_quiver.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_rcparams.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_sankey.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_scale.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_simplification.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_skew.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_sphinxext.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_spines.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_streamplot.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_style.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_subplots.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_table.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_testing.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_texmanager.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_text.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_textpath.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_ticker.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_tightlayout.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_transforms.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_triangulation.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_ttconv.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_type1font.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_units.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_usetex.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\test_widgets.py -> build\lib.win32-cpython-310\matplotlib\tests
      copying lib\matplotlib\tests\__init__.py -> build\lib.win32-cpython-310\matplotlib\tests
      creating build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\triangulation.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\tricontour.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\trifinder.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\triinterpolate.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\tripcolor.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\triplot.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\trirefine.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\tritools.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_triangulation.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tricontour.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_trifinder.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_triinterpolate.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tripcolor.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_triplot.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_trirefine.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tritools.py -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\__init__.py -> build\lib.win32-cpython-310\matplotlib\tri
      creating build\lib.win32-cpython-310\matplotlib\_api
      copying lib\matplotlib\_api\deprecation.py -> build\lib.win32-cpython-310\matplotlib\_api
      copying lib\matplotlib\_api\__init__.py -> build\lib.win32-cpython-310\matplotlib\_api
      creating build\lib.win32-cpython-310\matplotlib\backends\qt_editor
      copying lib\matplotlib\backends\qt_editor\figureoptions.py -> build\lib.win32-cpython-310\matplotlib\backends\qt_editor
      copying lib\matplotlib\backends\qt_editor\_formlayout.py -> build\lib.win32-cpython-310\matplotlib\backends\qt_editor
      copying lib\matplotlib\backends\qt_editor\__init__.py -> build\lib.win32-cpython-310\matplotlib\backends\qt_editor      creating build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\Duration.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\Epoch.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\EpochConverter.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\StrConverter.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\UnitDbl.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\UnitDblConverter.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\UnitDblFormatter.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      copying lib\matplotlib\testing\jpl_units\__init__.py -> build\lib.win32-cpython-310\matplotlib\testing\jpl_units
      creating build\lib.win32-cpython-310\mpl_toolkits
      creating build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\anchored_artists.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\axes_divider.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\axes_grid.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\axes_rgb.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\axes_size.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\inset_locator.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\mpl_axes.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\parasite_axes.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      copying lib\mpl_toolkits\axes_grid1\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1
      creating build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\angle_helper.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axes_divider.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axes_grid.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axes_rgb.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axislines.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axisline_style.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\axis_artist.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\floating_axes.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\grid_finder.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\grid_helper_curvelinear.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\parasite_axes.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      copying lib\mpl_toolkits\axisartist\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist
      creating build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      copying lib\mpl_toolkits\mplot3d\art3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      copying lib\mpl_toolkits\mplot3d\axes3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      copying lib\mpl_toolkits\mplot3d\axis3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      copying lib\mpl_toolkits\mplot3d\proj3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      copying lib\mpl_toolkits\mplot3d\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d
      creating build\lib.win32-cpython-310\mpl_toolkits\axes_grid1\tests
      copying lib\mpl_toolkits\axes_grid1\tests\conftest.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1\tests      copying lib\mpl_toolkits\axes_grid1\tests\test_axes_grid1.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1\tests
      copying lib\mpl_toolkits\axes_grid1\tests\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\axes_grid1\tests      creating build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\conftest.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests      copying lib\mpl_toolkits\axisartist\tests\test_angle_helper.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\test_axislines.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\test_axis_artist.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\test_floating_axes.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\test_grid_finder.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\test_grid_helper_curvelinear.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests
      copying lib\mpl_toolkits\axisartist\tests\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\axisartist\tests      creating build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      copying lib\mpl_toolkits\mplot3d\tests\conftest.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      copying lib\mpl_toolkits\mplot3d\tests\test_art3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      copying lib\mpl_toolkits\mplot3d\tests\test_axes3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      copying lib\mpl_toolkits\mplot3d\tests\test_legend3d.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      copying lib\mpl_toolkits\mplot3d\tests\__init__.py -> build\lib.win32-cpython-310\mpl_toolkits\mplot3d\tests
      creating build\lib.win32-cpython-310\matplotlib\mpl-data
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\fonts
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizThreeSymReg.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      creating build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\backends\web_backend\ipython_inline_figure.html -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\ptmb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-colorblind.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\zoom_to_rect_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\sample_data\eeg.dat -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data      copying lib\matplotlib\mpl-data\fonts\afm\phvb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSansMono-BoldOblique.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\subplots-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\_classic_test_patch.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXNonUni.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\help.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\subplots.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\_mpl-gallery.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\dark_background.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\pcrbo8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\zoom_to_rect.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pbkd8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\pagk8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\phvl8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-darkgrid.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\cmmi10.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\phvr8an.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      creating build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Times-Italic.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\plot_directive
      copying lib\matplotlib\mpl-data\plot_directive\plot_directive.css -> build\lib.win32-cpython-310\matplotlib\mpl-data\plot_directive
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-paper.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\images\zoom_to_rect-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\back.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\qt4_editor_options.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\animation.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\artist.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\axis.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_bases.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_managers.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\backend_tools.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\bezier.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\cbook.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\cm.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\collections.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\colorbar.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\colors.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\container.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\contour.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\dviread.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\figure.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\font_manager.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\ft2font.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\gridspec.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\hatch.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\image.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\layout_engine.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\legend.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\legend_handler.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\lines.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\markers.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\mathtext.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\mlab.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\offsetbox.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\patches.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\path.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\patheffects.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\quiver.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\rcsetup.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\sankey.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\scale.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\spines.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\stackplot.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\streamplot.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\table.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\texmanager.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\text.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\textpath.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\ticker.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\transforms.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\widgets.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_color_data.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_c_internal_utils.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_docstring.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_enums.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_image.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_path.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_pylab_helpers.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_qhull.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_tri.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\_ttconv.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\__init__.pyi -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\axes\_axes.pyi -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\_base.pyi -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\_secondary_axes.pyi -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\axes\__init__.pyi -> build\lib.win32-cpython-310\matplotlib\axes
      copying lib\matplotlib\backends\_backend_agg.pyi -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\_macosx.pyi -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\backends\_tkagg.pyi -> build\lib.win32-cpython-310\matplotlib\backends
      copying lib\matplotlib\projections\geo.pyi -> build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\projections\polar.pyi -> build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\projections\__init__.pyi -> build\lib.win32-cpython-310\matplotlib\projections
      copying lib\matplotlib\style\core.pyi -> build\lib.win32-cpython-310\matplotlib\style
      copying lib\matplotlib\testing\compare.pyi -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\conftest.pyi -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\decorators.pyi -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\widgets.pyi -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\testing\__init__.pyi -> build\lib.win32-cpython-310\matplotlib\testing
      copying lib\matplotlib\tri\_triangulation.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tricontour.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_trifinder.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_triinterpolate.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tripcolor.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_triplot.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_trirefine.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\tri\_tritools.pyi -> build\lib.win32-cpython-310\matplotlib\tri
      copying lib\matplotlib\_api\deprecation.pyi -> build\lib.win32-cpython-310\matplotlib\_api
      copying lib\matplotlib\_api\__init__.pyi -> build\lib.win32-cpython-310\matplotlib\_api
      copying lib\matplotlib\mpl-data\fonts\afm\pbkdi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\sample_data\msft.csv -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-whitegrid.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\sample_data\goog.npz -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-deep.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\images\zoom_to_rect.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXNonUniBolIta.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSerif-Italic.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\backends\web_backend\.prettierignore -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\mpl-data\fonts\afm\pplr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\hand.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\home-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images      copying lib\matplotlib\mpl-data\images\filesave.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pagko8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizFourSymReg.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-dark-palette.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\ttf\cmmi10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\pagdo8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\back_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\phvlo8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\subplots_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\qt4_editor_options.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pcrb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\qt4_editor_options_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\sample_data\embedding_in_wx3.xrc -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-white.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\backends\web_backend\package.json -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\mpl-data\sample_data\s1045.ima.gz -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Times-Bold.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\sample_data\data_x_x2_x3.csv -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSerif-Bold.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\forward.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\forward_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Courier.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\images\home_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\ttf\cmex10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\cmex10.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\pcrro8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\LICENSE_STIX -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\pbkli8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\ZapfDingbats.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\images\matplotlib.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\sample_data\Stocks.csv -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\backends\web_backend\.eslintrc.js -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\backends\web_backend\nbagg_uat.ipynb -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\mpl-data\images\help_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\home.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\putbi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\readme.txt -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\backends\web_backend\.prettierrc -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      creating build\lib.win32-cpython-310\matplotlib\backends\web_backend\css
      copying lib\matplotlib\backends\web_backend\css\page.css -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\css
      copying lib\matplotlib\mpl-data\images\help.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\backends\web_backend\single_figure.html -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizFiveSymReg.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\pcrr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\ptmbi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\back-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images      copying lib\matplotlib\mpl-data\stylelib\Solarize_Light2.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Courier-BoldOblique.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\stylelib\bmh.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-poster.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-talk.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\images\filesave.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\fivethirtyeight.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\phvbo8an.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\subplots.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-muted.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\cmtt10.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      creating build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data\axes_grid
      copying lib\matplotlib\mpl-data\sample_data\axes_grid\bivariate_normal.npy -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data\axes_grid
      copying lib\matplotlib\mpl-data\stylelib\classic.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-dark.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\pplb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Helvetica-BoldOblique.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\afm\putb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\pncri8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\STIXNonUniBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\ptmr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSans-Oblique.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSerifDisplay.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSans-BoldOblique.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\filesave-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXGeneral.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\stylelib\tableau-colorblind10.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\stylelib\fast.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib      copying lib\matplotlib\mpl-data\images\matplotlib_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\hand.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\ttf\cmss10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-ticks.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\cmsy10.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\afm\putri8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Helvetica-Oblique.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\afm\psyr.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\sample_data\grace_hopper.jpg -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizTwoSymReg.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\move_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\backends\web_backend\css\boilerplate.css -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\css
      copying lib\matplotlib\mpl-data\fonts\afm\phvbo8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSerif.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\pncbi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\afm\ptmri8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\help.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pzcmi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\forward-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\cmr10.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXGeneralItalic.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\filesave.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Helvetica.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSerif-BoldItalic.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\backends\web_backend\css\mpl.css -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\css
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizOneSymBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSansMono-Bold.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\sample_data\jacksboro_fault_dem.npz -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      creating build\lib.win32-cpython-310\matplotlib\backends\web_backend\js
      copying lib\matplotlib\backends\web_backend\js\mpl_tornado.js -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\js
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Times-Roman.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\images\filesave_large.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\help-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images      copying lib\matplotlib\mpl-data\fonts\afm\putr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\fonts\ttf\LICENSE_DEJAVU -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXGeneralBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizOneSymReg.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Courier-Bold.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\afm\phvro8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\kpsewhich.lua -> build\lib.win32-cpython-310\matplotlib\mpl-data
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Symbol.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\ttf\cmr10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSansDisplay.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXGeneralBolIta.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\move.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pncb8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\move.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\subplots.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-pastel.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\backends\web_backend\css\fbm.css -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\css
      copying lib\matplotlib\backends\web_backend\all_figures.html -> build\lib.win32-cpython-310\matplotlib\backends\web_backend
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSans-Bold.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-notebook.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\sample_data\membrane.dat -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\images\forward.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\_mpl-gallery-nogrid.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\matplotlibrc -> build\lib.win32-cpython-310\matplotlib\mpl-data
      copying lib\matplotlib\mpl-data\images\matplotlib.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\images\qt4_editor_options.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pncr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\sample_data\logo2.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSansMono.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizTwoSymBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSans.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\home.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\backends\web_backend\js\nbagg_mpl.js -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\js
      copying lib\matplotlib\mpl-data\images\hand.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pplbi8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\cmb10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Helvetica-Bold.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\sample_data\README.txt -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\py.typed -> build\lib.win32-cpython-310\matplotlib
      copying lib\matplotlib\mpl-data\sample_data\topobathy.npz -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\mpl-data\images\home.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\stylelib\ggplot.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\ttf\DejaVuSansMono-Oblique.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\back.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Times-BoldItalic.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizFourSymBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\afm\phvr8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\stylelib\grayscale.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\ttf\cmtt10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\stylelib\seaborn-v0_8-bright.mplstyle -> build\lib.win32-cpython-310\matplotlib\mpl-data\stylelib
      copying lib\matplotlib\mpl-data\fonts\afm\pplri8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\images\forward.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pagd8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\move.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\phvro8an.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\sample_data\Minduka_Present_Blue_Pack.png -> build\lib.win32-cpython-310\matplotlib\mpl-data\sample_data
      copying lib\matplotlib\backends\web_backend\js\mpl.js -> build\lib.win32-cpython-310\matplotlib\backends\web_backend\js
      copying lib\matplotlib\mpl-data\fonts\afm\phvb8an.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm      copying lib\matplotlib\mpl-data\fonts\ttf\STIXSizThreeSymBol.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\fonts\ttf\STIXNonUniIta.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\back.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pbkl8a.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\zoom_to_rect.pdf -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\afm\pzdr.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\afm
      copying lib\matplotlib\mpl-data\images\matplotlib.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images
      copying lib\matplotlib\mpl-data\fonts\ttf\cmsy10.ttf -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\ttf
      copying lib\matplotlib\mpl-data\images\move-symbolic.svg -> build\lib.win32-cpython-310\matplotlib\mpl-data\images      copying lib\matplotlib\mpl-data\fonts\pdfcorefonts\Courier-Oblique.afm -> build\lib.win32-cpython-310\matplotlib\mpl-data\fonts\pdfcorefonts
      running build_ext
      WARNING setuptools_scm._integration.setuptools pyproject.toml does not contain a tool.setuptools_scm section
      Extracting /project/freetype/freetype2/2.6.1/freetype-2.6.1.tar.gz
      Building freetype in build\freetype-2.6.1
      C:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\python.exe -c "import pathlib, shutil, sys
      dest = pathlib.Path(sys.argv[1])
      dest.write_text(shutil.which('msbuild'))
      " C:\Users\KenKen\AppData\Local\Temp\tmp3op60lzi\path
      "C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\\MSBuild\Current\Bin\amd64\msbuild.EXE" build\freetype-2.6.1\builds\windows\vc2010\freetype.sln /t:Clean;Build /p:Configuration=Release;Platform=Win32
      MSBuild version 17.7.2+d6990bcfa for .NET Framework
      Build started 10/20/2023 9:15:55 PM.

      Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" on node 1 (Clean;Build target(s)).
      ValidateSolutionConfiguration:
        Building solution configuration "Release|Win32".
      Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" (1) is building "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (2) on node 1 (Clean target(s)).
      CoreClean:
        Creating directory ".\..\..\..\objs\vc2010\Win32\Release\".
      Done Building Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (Clean target(s)).
      Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" (1) is building "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (2:2) on node 1 (default targets).
      C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\MSBuild\Microsoft\VC\v170\Microsoft.CppBuild.targets(541,5): warning MSB8029: The Intermediate directory or Output directory cannot reside under the Temporary directory as it could lead to issues with incremental build. [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        Creating directory ".\..\..\..\objs\vc2010\Win32\Release\freetype.tlog\".
      InitializeBuildStatus:
        Creating ".\..\..\..\objs\vc2010\Win32\Release\freetype.tlog\unsuccessfulbuild" because "AlwaysCreate" was specified.
        Touching ".\..\..\..\objs\vc2010\Win32\Release\freetype.tlog\unsuccessfulbuild".
      ClCompile:
        C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\bin\HostX86\x86\CL.exe /c /I..\..\..\include /nologo /W4 /WX- /diagnostics:column /MP /Ox /Ob2 /Oi /Oy /GT /D NDEBUG /D WIN32 /D _LIB /D _CRT_SECURE_NO_WARNINGS /D FT2_BUILD_LIBRARY /D _MBCS /GF /Gm- /EHsc /MD /GS /Gy /arch:SSE2 /fp:precise /fp:except- /Za /Zc:wchar_t /Zc:forScope /Zc:inline /Fo".\..\..\..\objs\vc2010\Win32\Release\\" /external:W4 /Gd /TC /wd4001 /analyze- /FC /errorReport:queue ..\..\..\src\autofit\autofit.c ..\..\..\src\base\ftbitmap.c ..\..\..\src\base\ftfstype.c ..\..\..\src\base\ftgasp.c ..\..\..\src\base\ftstroke.c ..\..\..\src\base\ftbbox.c ..\..\..\src\base\ftfntfmt.c ..\..\..\src\base\ftpfr.c ..\..\..\src\base\ftsynth.c ..\..\..\src\base\fttype1.c ..\..\..\src\base\ftwinfnt.c ..\..\..\src\base\ftlcdfil.c ..\..\..\src\base\ftgxval.c ..\..\..\src\base\ftotval.c ..\..\..\src\base\ftpatent.c
        autofit.c
        ftbitmap.c
        ftfstype.c
        ftgasp.c
        ftstroke.c
        ftbbox.c
        ftfntfmt.c
        ftpfr.c
        ftsynth.c
        fttype1.c
        ftwinfnt.c
        ftlcdfil.c
        ftgxval.c
        ftotval.c
        ftpatent.c
        C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\bin\HostX86\x86\CL.exe /c /I..\..\..\include /nologo /W4 /WX- /diagnostics:column /MP /O2 /Ob2 /Oi /Oy /GT /D NDEBUG /D WIN32 /D _LIB /D _CRT_SECURE_NO_WARNINGS /D FT2_BUILD_LIBRARY /D _MBCS /GF /Gm- /EHsc /MD /GS /Gy /arch:SSE2 /fp:precise /fp:except- /Za /Zc:wchar_t /Zc:forScope /Zc:inline /Fo".\..\..\..\objs\vc2010\Win32\Release\\" /external:W4 /Gd /TC /wd4001 /analyze- /FC /errorReport:queue ..\..\..\src\bdf\bdf.c ..\..\..\src\cff\cff.c ..\..\..\src\base\ftbase.c ..\..\..\src\cache\ftcache.c ..\..\..\src\base\ftglyph.c ..\..\..\src\gzip\ftgzip.c ..\..\..\src\base\ftinit.c ..\..\..\src\lzw\ftlzw.c ..\..\..\src\base\ftsystem.c ..\..\..\src\smooth\smooth.c ..\..\..\src\base\ftmm.c ..\..\..\src\pcf\pcf.c ..\..\..\src\pfr\pfr.c ..\..\..\src\psaux\psaux.c ..\..\..\src\pshinter\pshinter.c ..\..\..\src\psnames\psmodule.c ..\..\..\src\raster\raster.c ..\..\..\src\sfnt\sfnt.c ..\..\..\src\truetype\truetype.c ..\..\..\src\type1\type1.c ..\..\..\src\cid\type1cid.c ..\..\..\src\type42\type42.c ..\..\..\src\winfonts\winfnt.c
        bdf.c
        cff.c
        ftbase.c
        ftcache.c
        ftglyph.c
        ftgzip.c
        ftinit.c
        ftlzw.c
        ftsystem.c
      C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftutil.c(171): warning C4702: unreachable code [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        smooth.c
      C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftobjs.c(4711): warning C4702: unreachable code [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
      C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftoutln.c(962): warning C4701: potentially uninitialized local variable 'anchor' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
      C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftoutln.c(975): warning C4701: potentially uninitialized local variable 'in' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        ftmm.c
        pcf.c
        pfr.c
        psaux.c
        pshinter.c
        psmodule.c
        raster.c
        sfnt.c
        truetype.c
        type1.c
        type1cid.c
        type42.c
        winfnt.c
      C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\truetype\ttgload.c(1748): warning C4701: potentially uninitialized local variable 'outline' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\bin\HostX86\x86\CL.exe /c /I..\..\..\include /nologo /W4 /WX- /diagnostics:column /MP /O2 /Ob2 /Oi /Oy /GT /D NDEBUG /D WIN32 /D _LIB /D _CRT_SECURE_NO_WARNINGS /D FT2_BUILD_LIBRARY /D _MBCS /GF /Gm- /EHsc /MD /GS /Gy /arch:SSE2 /fp:precise /fp:except- /Zc:wchar_t /Zc:forScope /Zc:inline /Fo".\..\..\..\objs\vc2010\Win32\Release\\" /external:W4 /Gd /TC /wd4001 /analyze- /FC /errorReport:queue ..\ftdebug.c
        ftdebug.c
      Lib:
        C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\bin\HostX86\x86\Lib.exe /OUT:".\..\..\..\objs\vc2010\Win32\freetype261.lib" /NOLOGO /MACHINE:X86 /LTCG .\..\..\..\objs\vc2010\Win32\Release\autofit.obj
        .\..\..\..\objs\vc2010\Win32\Release\bdf.obj
        .\..\..\..\objs\vc2010\Win32\Release\cff.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftbase.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftbitmap.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftcache.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftdebug.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftfstype.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftgasp.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftglyph.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftgzip.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftinit.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftlzw.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftstroke.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftsystem.obj
        .\..\..\..\objs\vc2010\Win32\Release\smooth.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftbbox.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftfntfmt.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftmm.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftpfr.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftsynth.obj
        .\..\..\..\objs\vc2010\Win32\Release\fttype1.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftwinfnt.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftlcdfil.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftgxval.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftotval.obj
        .\..\..\..\objs\vc2010\Win32\Release\ftpatent.obj
        .\..\..\..\objs\vc2010\Win32\Release\pcf.obj
        .\..\..\..\objs\vc2010\Win32\Release\pfr.obj
        .\..\..\..\objs\vc2010\Win32\Release\psaux.obj
        .\..\..\..\objs\vc2010\Win32\Release\pshinter.obj
        .\..\..\..\objs\vc2010\Win32\Release\psmodule.obj
        .\..\..\..\objs\vc2010\Win32\Release\raster.obj
        .\..\..\..\objs\vc2010\Win32\Release\sfnt.obj
        .\..\..\..\objs\vc2010\Win32\Release\truetype.obj
        .\..\..\..\objs\vc2010\Win32\Release\type1.obj
        .\..\..\..\objs\vc2010\Win32\Release\type1cid.obj
        .\..\..\..\objs\vc2010\Win32\Release\type42.obj
        .\..\..\..\objs\vc2010\Win32\Release\winfnt.obj
        freetype.vcxproj -> C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\objs\vc2010\Win32\freetype261.lib
      FinalizeBuildStatus:
        Deleting file ".\..\..\..\objs\vc2010\Win32\Release\freetype.tlog\unsuccessfulbuild".
        Touching ".\..\..\..\objs\vc2010\Win32\Release\freetype.tlog\freetype.lastbuildstate".
      Done Building Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (default targets).
      Done Building Project "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" (Clean;Build target(s)).

      Build succeeded.

      "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" (Clean;Build target) (1) ->
      "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (default target) (2:2) ->
      (PrepareForBuild target) ->
        C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\MSBuild\Microsoft\VC\v170\Microsoft.CppBuild.targets(541,5): warning MSB8029: The Intermediate directory or Output directory cannot reside under the Temporary directory as it could lead to issues with incremental build. [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]


      "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.sln" (Clean;Build target) (1) ->
      "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj" (default target) (2:2) ->
      (ClCompile target) ->
        C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftutil.c(171): warning C4702: unreachable code [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftobjs.c(4711): warning C4702: unreachable code [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftoutln.c(962): warning C4701: potentially uninitialized local variable 'anchor' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\base\ftoutln.c(975): warning C4701: potentially uninitialized local variable 'in' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]
        C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\src\truetype\ttgload.c(1748): warning C4701: potentially uninitialized local variable 'outline' used [C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\matplotlib_b8e5839c0fe84e59a618762d440a65ab\build\freetype-2.6.1\builds\windows\vc2010\freetype.vcxproj]

          6 Warning(s)
          0 Error(s)

      Time Elapsed 00:00:24.70
      Copying build\freetype-2.6.1\objs\vc2010\Win32\freetype261.lib to build\freetype-2.6.1\objs\.libs\libfreetype.lib
      Extracting /download/qhull-2020-src-8.0.2.tgz
      building 'matplotlib.backends._backend_agg' extension
      creating build\temp.win32-cpython-310
      creating build\temp.win32-cpython-310\Release
      creating build\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg
      creating build\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg\extern
      creating build\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg\extern\agg24-svn
      creating build\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg\extern\agg24-svn\src
      creating build\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg\src
      "C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\bin\HostX86\x86\cl.exe" /c /nologo /O2 /W3 /GL /DNDEBUG /MD -DPY_ARRAY_UNIQUE_SYMBOL=MPL_matplotlib_backends__backend_agg_ARRAY_API -DNPY_NO_DEPRECATED_API=NPY_1_7_API_VERSION -D__STDC_FORMAT_MACROS=1 -DFREETYPE_BUILD_TYPE=local -Ibuild\freetype-2.6.1\include -Iextern/agg24-svn/include -IC:\Users\KenKen\AppData\Local\Temp\pip-build-env-nxsir_rj\overlay\Lib\site-packages\numpy\core\include -IC:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\include -IC:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\Include "-IC:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Tools\MSVC\14.37.32822\include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Auxiliary\VS\include" /EHsc /Tpextern\agg24-svn\src\agg_bezier_arc.cpp /Fobuild\temp.win32-cpython-310\Release\matplotlib.backends._backend_agg\extern\agg24-svn\src\agg_bezier_arc.obj
      agg_bezier_arc.cpp
      extern\agg24-svn\src\agg_bezier_arc.cpp(22): fatal error C1083: Cannot open include file: 'math.h': No such file or directory
      error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\BuildTools\\VC\\Tools\\MSVC\\14.37.32822\\bin\\HostX86\\x86\\cl.exe' failed with exit code 2
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for matplotlib
  Building wheel for pillow (pyproject.toml) ... error
  error: subprocess-exited-with-error

  × Building wheel for pillow (pyproject.toml) did not run successfully.
  │ exit code: 1
  ╰─> [199 lines of output]
      running bdist_wheel
      running build
      running build_py
      creating build
      creating build\lib.win32-cpython-310
      creating build\lib.win32-cpython-310\PIL
      copying src\PIL\BdfFontFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\BlpImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\BmpImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\BufrStubImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ContainerIO.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\CurImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\DcxImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\DdsImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\EpsImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ExifTags.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\features.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\FitsImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\FliImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\FontFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\FpxImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\FtexImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GbrImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GdImageFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GifImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GimpGradientFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GimpPaletteFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\GribStubImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\Hdf5StubImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\IcnsImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\IcoImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\Image.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageChops.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageCms.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageColor.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageDraw.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageDraw2.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageEnhance.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageFilter.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageFont.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageGrab.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageMath.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageMode.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageMorph.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageOps.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImagePalette.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImagePath.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageQt.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageSequence.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageShow.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageStat.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageTk.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageTransform.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImageWin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\ImtImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\IptcImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\Jpeg2KImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\JpegImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\JpegPresets.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\McIdasImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\MicImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\MpegImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\MpoImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\MspImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PaletteFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PalmImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PcdImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PcfFontFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PcxImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PdfImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PdfParser.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PixarImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PngImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PpmImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PsdImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PSDraw.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\PyAccess.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\QoiImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\SgiImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\SpiderImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\SunImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\TarIO.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\TgaImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\TiffImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\TiffTags.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\WalImageFile.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\WebPImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\WmfImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\XbmImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\XpmImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\XVThumbImagePlugin.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\_binary.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\_deprecate.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\_tkinter_finder.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\_util.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\_version.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\__init__.py -> build\lib.win32-cpython-310\PIL
      copying src\PIL\__main__.py -> build\lib.win32-cpython-310\PIL
      running egg_info
      writing src\Pillow.egg-info\PKG-INFO
      writing dependency_links to src\Pillow.egg-info\dependency_links.txt
      writing requirements to src\Pillow.egg-info\requires.txt
      writing top-level names to src\Pillow.egg-info\top_level.txt
      reading manifest file 'src\Pillow.egg-info\SOURCES.txt'
      reading manifest template 'MANIFEST.in'
      warning: no files found matching '*.c'
      warning: no files found matching '*.h'
      warning: no files found matching '*.sh'
      warning: no files found matching '*.txt'
      warning: no previously-included files found matching '.appveyor.yml'
      warning: no previously-included files found matching '.clang-format'
      warning: no previously-included files found matching '.coveragerc'
      warning: no previously-included files found matching '.editorconfig'
      warning: no previously-included files found matching '.readthedocs.yml'
      warning: no previously-included files found matching 'codecov.yml'
      warning: no previously-included files found matching 'renovate.json'
      warning: no previously-included files matching '.git*' found anywhere in distribution
      warning: no previously-included files matching '*.so' found anywhere in distribution
      no previously-included directories found matching '.ci'
      no previously-included directories found matching 'wheels'
      adding license file 'LICENSE'
      writing manifest file 'src\Pillow.egg-info\SOURCES.txt'
      running build_ext


      The headers or library files could not be found for zlib,
      a required dependency when compiling Pillow from source.

      Please see the install instructions at:
         https://pillow.readthedocs.io/en/latest/installation.html

      Traceback (most recent call last):
        File "<string>", line 988, in <module>
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\__init__.py", line 103, in setup
          return distutils.core.setup(**attrs)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\core.py", line 185, in setup
          return run_commands(dist)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\core.py", line 201, in run_commands
          dist.run_commands()
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\dist.py", line 969, in run_commands
          self.run_command(cmd)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\dist.py", line 989, in run_command
          super().run_command(command)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\normal\Lib\site-packages\wheel\bdist_wheel.py", line 364, in run
          self.run_command("build")
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\dist.py", line 989, in run_command
          super().run_command(command)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\command\build.py", line 131, in run
          self.run_command(cmd_name)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\cmd.py", line 318, in run_command
          self.distribution.run_command(command)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\dist.py", line 989, in run_command
          super().run_command(command)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\dist.py", line 988, in run_command
          cmd_obj.run()
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\command\build_ext.py", line 88, in run
          _build_ext.run(self)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\_distutils\command\build_ext.py", line 345, in run
          self.build_extensions()
        File "<string>", line 811, in build_extensions
      __main__.RequiredDependencyException: zlib

      During handling of the above exception, another exception occurred:

      Traceback (most recent call last):
        File "C:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\lib\site-packages\pip\_vendor\pyproject_hooks\_in_process\_in_process.py", line 353, in <module>
          main()
        File "C:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\lib\site-packages\pip\_vendor\pyproject_hooks\_in_process\_in_process.py", line 335, in main
          json_out['return_val'] = hook(**hook_input['kwargs'])
        File "C:\Users\KenKen\AppData\Local\Programs\Python\Python310-32\lib\site-packages\pip\_vendor\pyproject_hooks\_in_process\_in_process.py", line 251, in build_wheel
          return _build_backend().build_wheel(wheel_directory, config_settings,
        File "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\pillow_cdecef6fab6f43bb836b069cdf37a97b\_custom_build\backend.py", line 53, in build_wheel
          return super().build_wheel(wheel_directory, config_settings, metadata_directory)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\build_meta.py", line 434, in build_wheel
          return self._build_with_temp_dir(
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\build_meta.py", line 419, in _build_with_temp_dir
          self.run_setup()
        File "C:\Users\KenKen\AppData\Local\Temp\pip-install-g5ubxylj\pillow_cdecef6fab6f43bb836b069cdf37a97b\_custom_build\backend.py", line 47, in run_setup
          return super().run_setup(setup_script)
        File "C:\Users\KenKen\AppData\Local\Temp\pip-build-env-gq8w6v4n\overlay\Lib\site-packages\setuptools\build_meta.py", line 341, in run_setup
          exec(code, locals())
        File "<string>", line 1005, in <module>
      __main__.RequiredDependencyException:

      The headers or library files could not be found for zlib,
      a required dependency when compiling Pillow from source.

      Please see the install instructions at:
         https://pillow.readthedocs.io/en/latest/installation.html


      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for pillow
Failed to build matplotlib pillow
ERROR: Could not build wheels for matplotlib, pillow, which is required to install pyproject.toml-based projects

[notice] A new release of pip is available: 23.2.1 -> 23.3
[notice] To update, run: python.exe -m pip install --upgrade pip

C:\Users\KenKen>
