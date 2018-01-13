<Type Name="ResourceEncryptionKeyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceEncryptionKeyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceEncryptionKeyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceEncryptionKeyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、StorSimple のオブジェクトを管理する rest ベースの API
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.Get (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations への参照。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            リソースの暗号化キーの応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ResourceEncryptionKeyOperationsExtensions.GetAsync (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetResourceEncryptionKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations への参照。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            リソースの暗号化キーの応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>