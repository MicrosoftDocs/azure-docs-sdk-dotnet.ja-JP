<Type Name="StorageAccountKey" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey">
  <TypeSignature Language="C#" Value="public class StorageAccountKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountKey" />
  <TypeSignature Language="F#" Value="type StorageAccountKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="53c70-101">ストレージ アカウントのアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="53c70-101">An access key for the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="53c70-102">StorageAccountKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53c70-102">Initializes a new instance of the StorageAccountKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountKey (string keyName = null, string value = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt; permissions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string value, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyName As String = null, Optional value As String = null, Optional permissions As Nullable(Of KeyPermission) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey : string * string * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey (keyName, value, permissions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="permissions" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="53c70-103">キーの名前です。</span><span class="sxs-lookup"><span data-stu-id="53c70-103">Name of the key.</span></span></param>
        <param name="value"><span data-ttu-id="53c70-104">ベース 64 でエンコードされたキーの値。</span><span class="sxs-lookup"><span data-stu-id="53c70-104">Base 64-encoded value of the key.</span></span></param>
        <param name="permissions"><span data-ttu-id="53c70-105">完全なアクセス許可または、キー--読み取り専用のアクセス許可。</span><span class="sxs-lookup"><span data-stu-id="53c70-105">Permissions for the key -- read-only or full permissions.</span></span> <span data-ttu-id="53c70-106">使用可能な値が含まれます '読み取り'、'FULL'。</span><span class="sxs-lookup"><span data-stu-id="53c70-106">Possible values include: 'READ', 'FULL'</span></span></param>
        <summary>
            <span data-ttu-id="53c70-107">StorageAccountKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="53c70-107">Initializes a new instance of the StorageAccountKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c70-108">キーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="53c70-108">Gets name of the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt; Permissions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt; Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Permissions As Nullable(Of KeyPermission)" />
      <MemberSignature Language="F#" Value="member this.Permissions : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.KeyPermission&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c70-109">完全なアクセス許可またはキー--読み取り専用のアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="53c70-109">Gets permissions for the key -- read-only or full permissions.</span></span>
            <span data-ttu-id="53c70-110">使用可能な値が含まれます '読み取り'、'FULL'。</span><span class="sxs-lookup"><span data-stu-id="53c70-110">Possible values include: 'READ', 'FULL'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="53c70-111">取得は基本キーの値を 64 エンコード形式です。</span><span class="sxs-lookup"><span data-stu-id="53c70-111">Gets base 64-encoded value of the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>