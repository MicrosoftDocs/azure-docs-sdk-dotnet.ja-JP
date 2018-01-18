<Type Name="CredentialType" FullName="System.Fabric.CredentialType">
  <TypeSignature Language="C#" Value="public enum CredentialType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CredentialType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CredentialType" />
  <TypeSignature Language="VB.NET" Value="Public Enum CredentialType" />
  <TypeSignature Language="F#" Value="type CredentialType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="36e72-101">セキュリティ資格情報の有効な種類を定義します。</span><span class="sxs-lookup"><span data-stu-id="36e72-101">Defines the valid kinds of security credentials.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="Claims" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType Claims = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.Claims" />
      <MemberSignature Language="VB.NET" Value="Claims" />
      <MemberSignature Language="F#" Value="Claims = 3" Usage="System.Fabric.CredentialType.Claims" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="36e72-102">STS (セキュリティ トークン サービス) から取得したクレーム トークンです。</span><span class="sxs-lookup"><span data-stu-id="36e72-102">The claims token acquired from STS (security token service).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.CredentialType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="36e72-103">ない資格情報が定義されている (既定値)。</span><span class="sxs-lookup"><span data-stu-id="36e72-103">No credential defined (default).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Windows">
      <MemberSignature Language="C#" Value="Windows" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType Windows = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.Windows" />
      <MemberSignature Language="VB.NET" Value="Windows" />
      <MemberSignature Language="F#" Value="Windows = 2" Usage="System.Fabric.CredentialType.Windows" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="36e72-104">Active directory ドメインの資格情報。</span><span class="sxs-lookup"><span data-stu-id="36e72-104">The active directory domain credential.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="X509">
      <MemberSignature Language="C#" Value="X509" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CredentialType X509 = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CredentialType.X509" />
      <MemberSignature Language="VB.NET" Value="X509" />
      <MemberSignature Language="F#" Value="X509 = 1" Usage="System.Fabric.CredentialType.X509" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CredentialType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="36e72-105">X509 証明書。</span><span class="sxs-lookup"><span data-stu-id="36e72-105">The X509 certificate.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>