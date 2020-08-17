## 1. Generate model per table

* it should be capital first letter and singular
* belongs_to
  * quicklly create associations

## 2. Associations

* has_many
* has_one
* for file attachment (ActiveStorage)
  * has_one_attached
  * has_many_attached
* belongs_to

## 3. Validations

* inclusion for enum
  * e.g. inclusion: { in: ModelName.PluralEnum.keys }
* validates_numericality
* presence: true/false

