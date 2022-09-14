# GAMS language for Visual Studio Code

Provides syntax highlighting for `.gms` and `.inc` files and shortcuts for running GAMS models.

## GAMS language

The General Algebraic Modeling System (GAMS) is a high-level modeling system for mathematical programming and optimization. It consists of a language compiler and a stable of integrated high-performance solvers. GAMS is tailored for complex, large scale modeling applications, and allows you to build large maintainable models that can be adapted quickly to new situations.

GAMS is the property of GAMS Software GmbH (http://www.gams.com).

## GAMS Comments

In GAMS, by default, block comments are delineated by **$ONTEXT**/**$OFFTEXT**, 
and line comments are started by a star **\***.

This package also adds the comment highlighting for end of line **#**, **!!** and **//**,
and the inline comments delineated by **/\*\* \*\*/**.

In order to GAMS to process these new comment conventions,
you need to add in your code some of these commands:

	$eolcom //
	$eolcom #
	$eolcom !!
	$inlinecom /* */

## Support

Please open an issue in the repository at https://github.com/lolow/gams.