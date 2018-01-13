<Type Name="AuthenticationType" FullName="Microsoft.Azure.Devices.AuthenticationType">
  <TypeSignature Language="C#" Value="public enum AuthenticationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AuthenticationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.AuthenticationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum AuthenticationType" />
  <TypeSignature Language="F#" Value="type AuthenticationType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0c37d-101">デバイスで使用される認証の種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="0c37d-101">Used to specify the authentication type used by a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CertificateAuthority">
      <MemberSignature Language="C#" Value="CertificateAuthority" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.AuthenticationType CertificateAuthority = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.AuthenticationType.CertificateAuthority" />
      <MemberSignature Language="VB.NET" Value="CertificateAuthority" />
      <MemberSignature Language="F#" Value="CertificateAuthority = 2" Usage="Microsoft.Azure.Devices.AuthenticationType.CertificateAuthority" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="certificateAuthority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.AuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c37d-102">証明機関</span><span class="sxs-lookup"><span data-stu-id="0c37d-102">Certificate Authority</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Sas">
      <MemberSignature Language="C#" Value="Sas" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.AuthenticationType Sas = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.AuthenticationType.Sas" />
      <MemberSignature Language="VB.NET" Value="Sas" />
      <MemberSignature Language="F#" Value="Sas = 0" Usage="Microsoft.Azure.Devices.AuthenticationType.Sas" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="sas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.AuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c37d-103">共有アクセス キー</span><span class="sxs-lookup"><span data-stu-id="0c37d-103">Shared Access Key</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SelfSigned">
      <MemberSignature Language="C#" Value="SelfSigned" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Devices.AuthenticationType SelfSigned = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.AuthenticationType.SelfSigned" />
      <MemberSignature Language="VB.NET" Value="SelfSigned" />
      <MemberSignature Language="F#" Value="SelfSigned = 1" Usage="Microsoft.Azure.Devices.AuthenticationType.SelfSigned" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="selfSigned")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.AuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c37d-104">自己署名証明書</span><span class="sxs-lookup"><span data-stu-id="0c37d-104">Self-signed certificate</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>