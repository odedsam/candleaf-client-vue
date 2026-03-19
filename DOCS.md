# DOCS

## Purpose

- This file is the high-level documentation index for `candleaf-client-vue`.
- It summarizes the repo layout and points to the detailed project docs generated alongside it.
- It is intentionally verbose so the project can be scanned quickly without opening source files first.
- Every line below is derived from files present in the repository tree at generation time.

## Documentation Set

- README.md: broad repository overview, dependency inventory, and source map
- docs/architecture.md: system structure, execution flow, and integration boundaries
- docs/development.md: scripts, setup workflow, configuration, and day-to-day development touchpoints
- docs/features.md: route, page, module, service, and feature inventory

## Repository Profile

- Name: `candleaf-client-vue`
- Kind: `frontend`
- Runtime: `Node.js`
- Framework: `Vue`
- Rendering or execution model: `Single-page application style client runtime`
- Package manager metadata: `Unknown`

## Scripts Snapshot

- `clean`: `rimraf ./dist`
- `dev`: `vite`
- `build`: `pnpm run clean && vue-tsc --build && vite build`
- `preview`: `vite preview`
- `test:unit`: `vitest`
- `build-only`: `vite build`
- `type-check`: `vue-tsc --build`
- `lint`: `eslint . --fix`
- `format`: `prettier --write src/`
- `play`: `pnpm exec playwright test --headed`
- `test`: `vitest`
- `test:ui`: `vitest --ui`
- `test:coverage`: `vitest --coverage`

## Environment Variable Snapshot

- `NODE_ENV`
- `VITE_BACKEND_URL`
- `VITE_BASE_PATH`
- `VITE_GOOGLE_CLIENT_ID`
- `VITE_STRIPE_PK`

## Top-Level Directories

- `.github/`
- `.vscode/`
- `docs/`
- `playwright-report/`
- `public/`
- `src/`
- `test-results/`
- `tests/`

## Top-Level Files

- `.gitignore`
- `.prettierrc`
- `DOCS.md`
- `LICENSE.txt`
- `README.md`
- `components.d.ts`
- `env.d.ts`
- `eslint.config.ts`
- `index.html`
- `package.json`
- `playwright.config.ts`
- `pnpm-lock.yaml`
- `tsconfig.json`
- `vercel.json`
- `vite.config.ts`
- `vitest.config.ts`

## Integration Snapshot

- Axios is declared for HTTP calls
- Zod validation is declared
- Pinia is declared

## Authentication Snapshot

- Repository contains auth-related source files or routes
- Repository contains session-related source files

## Database Snapshot

- Confirmed database/storage implementation is not fully documented in the scanned files

## Primary Source Areas

- `src/` is present
- `tests/` is present
- `public/` is present

## Detailed File Inventory

- `.github/dependabot.yml`
- `.prettierrc`
- `components.d.ts`
- `env.d.ts`
- `eslint.config.ts`
- `index.html`
- `package.json`
- `playwright.config.ts`
- `pnpm-lock.yaml`
- `src/App.vue`
- `src/assets/globals.css`
- `src/components/base/BaseButton.vue`
- `src/components/base/BaseCheckbox.vue`
- `src/components/base/BaseDropDown.vue`
- `src/components/base/BaseError.vue`
- `src/components/base/BaseIcon.vue`
- `src/components/base/BaseInput.vue`
- `src/components/base/BaseSelect.vue`
- `src/components/base/PasswordInput.vue`
- `src/components/features/auth/GoogleLogin.vue`
- `src/components/features/auth/RegisterUser.vue`
- `src/components/features/checkout/AddressAutoComplete.vue`
- `src/components/features/checkout/BillingAddress.vue`
- `src/components/features/checkout/CheckLoc.vue`
- `src/components/features/checkout/CheckoutHeader.vue`
- `src/components/features/checkout/CheckoutNewsLetter.vue`
- `src/components/features/checkout/InfoDisplay.vue`
- `src/components/features/checkout/OrderDetails.vue`
- `src/components/features/checkout/PaymentConfirmation.vue`
- `src/components/features/checkout/PaymentMethods.vue`
- `src/components/features/checkout/ShippingMethod.vue`
- `src/components/features/checkout/StepButtons.vue`
- `src/components/features/orders/OrdersList.vue`
- `src/components/features/orders/TrackingOrder.vue`
- `src/components/features/orders/TrackingStatus.vue`
- `src/components/features/products/CustomRadio.vue`
- `src/components/features/products/DetailsSection.vue`
- `src/components/features/products/IngredientsComp.vue`
- `src/components/features/products/ProductCard.vue`
- `src/components/features/products/ProductImage.vue`
- `src/components/features/products/RadioInput.vue`
- `src/components/features/products/SelectDelivery.vue`
- `src/components/features/products/SelectDropDown.vue`
- `src/components/features/products/SubscriptionSelector.vue`
- `src/components/features/user/UserProfile.vue`
- `src/components/features/user/UserProfileSec.vue`
- `src/components/features/wishlist/WishList.vue`
- `src/components/feedback/EmptyState.vue`
- `src/components/feedback/ErrorMessage.vue`
- `src/components/feedback/ErrorResponse.vue`
- `src/components/feedback/FetchStatus.vue`
- `src/components/forms/LoginForm.vue`
- `src/components/forms/StepOne.vue`
- `src/components/layout/MenuBar.vue`
- `src/components/layout/MobileMenu.vue`
- `src/components/layout/NavBar.vue`
- `src/components/layout/NavSettings.vue`
- `src/components/layout/SiteFooter.vue`
- `src/components/layout/SiteHeader.vue`
- `src/components/sections/CatalogGrid.vue`
- `src/components/sections/FeaturesInfo.vue`
- `src/components/sections/HeroSummary.vue`
- `src/components/sections/HomeHero.vue`
- `src/components/sections/PeopleReview.vue`
- `src/components/sections/PopularPr.vue`
- `src/components/sections/TestimonialsComp.vue`
- `src/components/shared/AppLoader.vue`
- `src/components/shared/CartItem.vue`
- `src/components/shared/CartModal.vue`
- `src/components/shared/HelperMessage.vue`
- `src/components/shared/QuantityInput.vue`
- `src/components/shared/QuantitySelector.vue`
- `src/components/shared/StripeTest.vue`
- `src/components/shared/ThemeToggle.vue`
- `src/components/shared/UiCredit.vue`
- `src/components/ui/BreadCrumb.vue`
- `src/components/ui/CartIcon.vue`
- `src/components/ui/CustomSelect.vue`
- `src/components/ui/DividerFooter.vue`
- `src/components/ui/LogoIcon.vue`
- `src/components/ui/UserAvatar.vue`
- `src/composables/useAuth.ts`
- `src/composables/useCart.ts`
- `src/composables/useCustomStorage.ts`
- `src/composables/useDebouncer.ts`
- `src/composables/useMultiStep.ts`
- `src/composables/useNavigateToProduct.ts`
- `src/composables/useOrders.ts`
- `src/composables/useValidation.ts`
- `src/composables/useWishlist.ts`
- `src/layouts/AuthLayout.vue`
- `src/layouts/CheckoutLayout.vue`
- `src/layouts/DefaultLayout.vue`
- `src/main.ts`
- `src/router/index.ts`
- `src/router/router.middleware.ts`
- `src/services/addressService.ts`
- `src/services/authService.ts`
- `src/services/authSessionService.ts`
- `src/services/index.ts`
- `src/services/productService.ts`
- `src/services/user.ts`
- `src/stores/authSessionStore.ts`
- `src/stores/authStore.ts`
- `src/stores/cartStore.ts`
- `src/stores/checkoutStore.ts`
- `src/stores/orderStore.ts`
- `src/stores/orderTrackingStore.ts`
- `src/stores/paymentStore.ts`
- `src/stores/productStore.ts`
- `src/stores/uiStore.ts`
- `src/stores/userStore.ts`
- `src/stores/wishListStore.ts`
- `src/types/User.ts`
- `src/types/constants.ts`
- `src/types/global.d.ts`
- `src/types/icon.d.ts`
- `src/types/index.ts`
- `src/utils/constants.ts`
- `src/utils/cookieStore.ts`
- `src/utils/feedBack.ts`
- `src/utils/formatters.ts`
- `src/utils/index.ts`
- `src/utils/loadGoogleScript.ts`
- `src/utils/stripe.ts`
- `src/utils/toaster.ts`
- `src/utils/tryCatch.ts`
- `src/validations/authValidation.ts`
- `src/validations/formValidations.ts`
- `src/views/AboutView.vue`
- `src/views/ContactView.vue`
- `src/views/HomeView.vue`
- `src/views/NotFoundView.vue`
- `src/views/TestView.vue`
- `src/views/auth/ForgotPassword.vue`
- `src/views/auth/LoginSuccess.vue`
- `src/views/auth/LoginView.vue`
- `src/views/auth/ResetPassword.vue`
- `src/views/checkout/CartView.vue`
- `src/views/checkout/ConfirmationView.vue`
- `src/views/checkout/DetailsView.vue`
- `src/views/checkout/PaymentView.vue`
- `src/views/checkout/ShippingView.vue`
- `src/views/orders/OrderTrackingView.vue`
- `src/views/products/ProductIdView.vue`
- `src/views/products/ProductsView.vue`
- `src/views/user/UserOrderDetailsView.vue`
- `src/views/user/UserProfileView.vue`
- `src/vite-env.d.ts`
- `tests/e2e/forms/checkout-flow.spec.ts`
- `tsconfig.json`
- `vercel.json`
- `vite.config.ts`
- `vitest.config.ts`

## Known Unknowns

- Deployment platform configuration was not explicitly confirmed from a Render manifest
- No explicit route or entry inventory could be categorized from the scanned source files
