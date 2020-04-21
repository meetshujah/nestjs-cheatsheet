# NestJS Cheatsheet

## Basic CURD 
```
import { Controller, Get } from '@nestjs/common';

@Controller('cats')
export class CatsController {
  @Get()
  findAll(): string {
    return 'this is get method';
  }

  @Post()
  findAll(): string {
    return 'this is post method';
  }

  @Put()
  findAll(): string {
    return 'this is put method';
  }

  @Delete()
  findAll(): string {
    return 'this is delete method';
  }
}
```