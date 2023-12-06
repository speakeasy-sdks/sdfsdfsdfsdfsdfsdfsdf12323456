<!-- Start SDK Example Usage [usage] -->
```python
import sdf

s = sdf.Sdf()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->