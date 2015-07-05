# duXorFormCheck


Klasa je pisana kao dodatak Bootstrap framework-a, za potrebe aktivne provjere unesenih podataka forme.

# Detaljno objašnjenje je u pripremi, ispod je navedeno samo osnovni primjer korištenja!

**HTML**  

```html
<form id="forma" class="form-horizontal">
	<div id="dime" class="form-group has-feedback">
		<label for="ime" class="control-label col-sm-2">Ime</label>	
		<div class="col-sm-10">
			<input id="ime" name="ime" class="form-control" placeholder="Unesite vaše ime">
			<span id="sime" class="glyphicon form-control-feedback"></span>
		</div>
	</div>
	<div class="form-group">
		<div class="col-sm-2"></div>
		<div class="col-sm-10">
			<button type="button" class="btn btn-lg btn-success" onClick="duXorFormCheck.submit('forma')">Submit</button>
		</div>
	</div>
</form>
```

# Autor

> # *Broje se samo rezultati!*
> Dušan Perišić
> [dusanperisic.com](https://dusanperisic.com) 

# [Demo](http://test.najsmestaj.com) 

> Demo se može pogledati na svim kontakt formama, kao i na formi za rezervaciju.