<Type Name="Protocol" FullName="Microsoft.Azure.Documents.Client.Protocol">
  <TypeSignature Language="C#" Value="public enum Protocol" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed Protocol extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.Protocol" />
  <TypeSignature Language="VB.NET" Value="Public Enum Protocol" />
  <TypeSignature Language="F#" Value="type Protocol = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            DocumentClient によって Azure Cosmos DB サービスとの通信に使用するプロトコルを指定します。
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.ConnectionMode" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />
    <example>
      <code language="c#"><![CDATA[
            DocumentClient client = new DocumentClient(endpointUri, masterKey, new ConnectionPolicy 
            { 
                ConnectionMode = ConnectionMode.Direct,
                ConnectionProtocol = Protocol.Tcp
            }); 
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Https">
      <MemberSignature Language="C#" Value="Https" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.Protocol Https = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.Protocol.Https" />
      <MemberSignature Language="VB.NET" Value="Https" />
      <MemberSignature Language="F#" Value="Https = 0" Usage="Microsoft.Azure.Documents.Client.Protocol.Https" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.Protocol</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            HTTPS プロトコルを指定します。
            </summary>
        <remarks>既定の接続。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.Protocol Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.Protocol.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.Azure.Documents.Client.Protocol.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.Protocol</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            TCP のカスタム バイナリ プロトコルを指定します。
            </summary>
        <remarks>パフォーマンスが向上します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>