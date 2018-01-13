<Type Name="ServiceNameFormat" FullName="Microsoft.ServiceFabric.Services.ServiceNameFormat">
  <TypeSignature Language="C#" Value="public static class ServiceNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.ServiceNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNameFormat" />
  <TypeSignature Language="F#" Value="type ServiceNameFormat = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスは、コードから、マニフェスト内のさまざまなアイテムの名前を派生させるためのロジックを提供します。 API の名前が指定されていないと framework の型が既定をサービスの種類から派生したわかりやすい名前にする必要がある framework コンポーネントによって使用されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetEndpointName">
      <MemberSignature Language="C#" Value="public static string GetEndpointName (Type serviceInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetEndpointName(class System.Type serviceInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetEndpointName (serviceInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName serviceInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">サービス インターフェイスの型名。</param>
        <summary>
            特定のサービス型の既定のエンドポイント リソース名を取得します。
            </summary>
        <returns>エンドポイント リソースの名前。</returns>
        <remarks>
          <list type="bullet">
            <item>
                    型の名前が場合<code>IMyService</code>、このメソッドが戻る<code>MyServiceEndpoint</code>エンドポイント リソースの名前とします。
                </item>
            <item>
                    型の名前が場合<code>Foo</code>、このメソッドが戻る<code>FooServiceEndpoint</code>エンドポイント リソースの名前とします。
                </item>
          </list>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>