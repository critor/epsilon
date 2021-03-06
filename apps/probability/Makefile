apps += Probability::App
app_headers += apps/probability/app.h

app_src += $(addprefix apps/probability/,\
  app.cpp \
  calculation/calculation.cpp \
  calculation/discrete_calculation.cpp \
  calculation/left_integral_calculation.cpp \
  calculation/right_integral_calculation.cpp \
  calculation/finite_integral_calculation.cpp \
  calculation_controller.cpp \
  calculation_cell.cpp \
  calculation_type_controller.cpp \
  cell.cpp \
  image_cell.cpp \
  law/binomial_law.cpp \
  law/erf_inv.cpp \
  law/exponential_law.cpp \
  law/law.cpp \
  law/normal_law.cpp \
  law/poisson_law.cpp \
  law/two_parameter_law.cpp \
  law/uniform_law.cpp \
  law_controller.cpp \
  law_curve_view.cpp \
  parameters_controller.cpp \
  responder_image_cell.cpp \
)

i18n_files += $(addprefix apps/probability/,\
  base.de.i18n\
  base.en.i18n\
  base.es.i18n\
  base.fr.i18n\
  base.pt.i18n\
)

tests += $(addprefix apps/probability/test/,\
  erf_inv.cpp\
)

# Image dependencies

$(eval $(call depends_on_image,apps/probability/app.cpp,apps/probability/probability_icon.png))

$(eval $(call depends_on_image,apps/probability/law_controller.cpp,$(addprefix apps/probability/images/, \
  binomial_icon.png \
  exponential_icon.png \
  focused_binomial_icon.png \
  focused_exponential_icon.png \
  focused_normal_icon.png \
  focused_poisson_icon.png \
  focused_uniform_icon.png \
  normal_icon.png \
  poisson_icon.png \
  uniform_icon.png \
)))

$(eval $(call depends_on_image,$(addprefix apps/probability/,calculation_type_controller.cpp calculation_controller.cpp),$(addprefix apps/probability/images/, \
  calcul1_icon.png \
  calcul2_icon.png \
  calcul3_icon.png \
  calcul4_icon.png \
  focused_calcul1_icon.png \
  focused_calcul2_icon.png \
  focused_calcul3_icon.png \
  focused_calcul4_icon.png \
)))
