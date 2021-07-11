CHANGELOG
=========

6.0
---

 * `TokenInterface` does not extend `Serializable` anymore
 * Remove all classes in the `Core\Encoder\`  sub-namespace, use the `PasswordHasher` component instead
 * Remove methods `getPassword()` and `getSalt()` from `UserInterface`, use `PasswordAuthenticatedUserInterface`
   or `LegacyPasswordAuthenticatedUserInterface` instead

5.4
---

 * Deprecate setting the 4th argument (`$alwaysAuthenticate`) to `true` and not setting the
   5th argument (`$exceptionOnNoToken`) to `false` of `AuthorizationChecker`

5.3
---

The CHANGELOG for version 5.3 and earlier can be found at https://github.com/symfony/symfony/blob/5.3/src/Symfony/Component/Security/CHANGELOG.md