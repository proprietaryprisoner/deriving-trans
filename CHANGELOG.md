# Revision history for deriving-trans

## 0.3.1.0 *08 Feb 2022*

* Add `MonadFix` instance to `Elevator`.

## 0.3.0.0 *04 Feb 2022*

* Add "base-case" instances for both lazy and strict transformers (from mtl) to `ComposeT`.
* Add `Alternative` and `MonadPlus` instances to `Elevator`.
* Add `MonadFail` instance to `Elevator`.
* Add `MonadCont` instances to `Elevator` and `ComposeT`.
* Add `MonadCont` "base-case" instance for `ContT` to `ComposeT`.
* Add `MonadRWS` instances to `Elevator` and `ComposeT`. It's not quite clear, whether this is necessary
* Add "base-case" instances for `RWST` to `ComposeT`.

## 0.2.2.1 *01 Feb 2022*

* Polish Haddock comments.

## 0.2.2.0 *30 Jan 2022*

* Add "base-case" instances for mtl's type classes to `ComposeT`.
* Add Haddock examples and improve comments.

## 0.2.1.0 *27 Jan 2022*

* Add `MonadTrans` and `MonadTransControl` instances to `Elevator`.
* Use StandaloneKindSignatures.
* Add Haddock documentation.

## 0.2.0.0 *25 Jan 2022*

* Completely change the idea of this project. Pretty much everything has been changed.

## 0.1.0.0 *19 Jun 2021*

* First version. Released on an unsuspecting world.
