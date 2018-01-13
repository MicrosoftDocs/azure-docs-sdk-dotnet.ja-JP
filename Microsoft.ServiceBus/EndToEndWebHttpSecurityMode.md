<Type Name="EndToEndWebHttpSecurityMode" FullName="Microsoft.ServiceBus.EndToEndWebHttpSecurityMode">
  <TypeSignature Language="C#" Value="public enum EndToEndWebHttpSecurityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EndToEndWebHttpSecurityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum EndToEndWebHttpSecurityMode" />
  <TypeSignature Language="F#" Value="type EndToEndWebHttpSecurityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>使用できるセキュリティの種類を指定、<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceBus.EndToEndWebHttpSecurityMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndWebHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>セキュリティが HTTP 要求で使用されていないことを示します。</summary>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="Transport" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Transport = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode.Transport" />
      <MemberSignature Language="VB.NET" Value="Transport" />
      <MemberSignature Language="F#" Value="Transport = 1" Usage="Microsoft.ServiceBus.EndToEndWebHttpSecurityMode.Transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndWebHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>トランスポート レベルのセキュリティが必要であることを示しますクライアントは、HTTPS を使用して、サービス エンドポイントと通信する必要があります。</summary>
      </Docs>
    </Member>
  </Members>
</Type>