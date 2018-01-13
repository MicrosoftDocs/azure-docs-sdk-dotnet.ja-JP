<Type Name="IWithCustomDomain" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain">
  <TypeSignature Language="C#" Value="public interface IWithCustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCustomDomain" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCustomDomain" />
  <TypeSignature Language="F#" Value="type IWithCustomDomain = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アカウントに関連付けるカスタム ドメインを指定するストレージ アカウント定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain customDomain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
      </Parameters>
      <Docs>
        <param name="customDomain">ストレージ アカウントに割り当てられているユーザーのドメイン。</param>
        <summary>
            ストレージ アカウントに割り当てられたユーザー ドメインを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ストレージ アカウント定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">カスタム ドメイン名は、CNAME ソース。</param>
        <summary>
            ストレージ アカウントに割り当てられたユーザー ドメインを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ストレージ アカウント定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain (string name, bool useSubDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithCustomDomain(string name, bool useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain.WithCustomDomain(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String, useSubDomain As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string * bool -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCustomDomain.WithCustomDomain (name, useSubDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">カスタム ドメイン名は、CNAME ソース。</param>
        <param name="useSubDomain">間接 CName 検証が有効になっているかどうか。</param>
        <summary>
            ストレージ アカウントに割り当てられたユーザー ドメインを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ストレージ アカウント定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>