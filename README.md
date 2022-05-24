# QA Automation Challenge Backend

This project is part of the QA Tech Challenge where we have to implement a REST API automation over a demo pet store: https://petstore.swagger.io/

## Automation Steps

• Get "available" pets. Assert expected result.

• Post a new available pet to the store. Assert new pet added.

• Update this pet status to "sold". Assert status updated.

• Delete this pet. Assert deletion.

## Tech Stack

**Tool:** Postman

## Running Tests

To run tests in Postman, you can use Postman Collection Runner.

## API Reference

#### Get available pets

``http
  GET /pet/findByStatus{status}
``

| Parameter | Type     |
| :-------- | :------- | 
| `status`  | `string` | 

#### Add new pet

``http
  POST /pet
``

#### Update pet status

``http
  GET /pet/${id}
``

| Parameter | Type     | 
| :-------- | :------- | 
| `petId`   | `string` |


#### Delete pet by Id

``http
  DELETE /pet/${petId}
``

| Parameter | Type     |
| :-------- | :------- |
| `id`      | `string` |
| `api_key` | `string` | 
