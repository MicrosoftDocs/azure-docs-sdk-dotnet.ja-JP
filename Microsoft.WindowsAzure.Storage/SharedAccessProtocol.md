<Type Name="SharedAccessProtocol" FullName="Microsoft.WindowsAzure.Storage.SharedAccessProtocol">
  <TypeSignature Language="C#" Value="public enum SharedAccessProtocol" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SharedAccessProtocol extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.SharedAccessProtocol" />
  <TypeSignature Language="VB.NET" Value="Public Enum SharedAccessProtocol" />
  <TypeSignature Language="F#" Value="type SharedAccessProtocol = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            一連の共有アクセス ポリシーのアカウントの可能な符号付きプロトコルを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HttpsOnly">
      <MemberSignature Language="C#" Value="HttpsOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol HttpsOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.SharedAccessProtocol.HttpsOnly" />
      <MemberSignature Language="VB.NET" Value="HttpsOnly" />
      <MemberSignature Language="F#" Value="HttpsOnly = 1" Usage="Microsoft.WindowsAzure.Storage.SharedAccessProtocol.HttpsOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.SharedAccessProtocol</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            付与 https のみを介して SAS を使用する権限です。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="HttpsOrHttp">
      <MemberSignature Language="C#" Value="HttpsOrHttp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol HttpsOrHttp = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.SharedAccessProtocol.HttpsOrHttp" />
      <MemberSignature Language="VB.NET" Value="HttpsOrHttp" />
      <MemberSignature Language="F#" Value="HttpsOrHttp = 2" Usage="Microsoft.WindowsAzure.Storage.SharedAccessProtocol.HttpsOrHttp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.SharedAccessProtocol</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Https または http 付与経由 SAS を使用する権限です。 すべてのアクセス権をまったく指定しないと同じです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>