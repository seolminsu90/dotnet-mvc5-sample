# dotnet-mvc5-sample
.net framework OLD MVC5 sample

매번 자바 스프링만 작업하다가 C#/.net 환경 공부가 필요해서 
공홈 자습서 따라한 프로젝트
.net framework 4.7.2 기반으로 mvc5 구성

- C# ? 자동관리
- .net framework 4.7.2
- MVC 5

### Route 설정 관련 메모

```bash
// 컨트롤러 메서드에 라우트 설정 가능하도록 설정(라우트 config에 추가)
config.MapHttpAttributeRoutes(); 

// 컨트롤러 메서드에 개별 라우트 경로 표기 가능
[Route("customers/{customerId}/orders")]
public IEnumerable<Order> GetOrdersByCustomer(int customerId) { ... }
```


### 기타
- 예제들이 구성이 다 비슷하다. EF를 사용안하는 방식을 쓸 텐데.
- Razor Page / ASPX 관련 공부를 해야겠다.

