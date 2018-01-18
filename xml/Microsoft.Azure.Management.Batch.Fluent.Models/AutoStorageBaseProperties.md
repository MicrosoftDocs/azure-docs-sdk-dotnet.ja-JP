<Type Name="AutoStorageBaseProperties" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties">
  <TypeSignature Language="C#" Value="public class AutoStorageBaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoStorageBaseProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoStorageBaseProperties" />
  <TypeSignature Language="F#" Value="type AutoStorageBaseProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f1356-101">自動ストレージ アカウントに関連するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f1356-101">The properties related to auto storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageBaseProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f1356-102">AutoStorageBaseProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f1356-102">Initializes a new instance of the AutoStorageBaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageBaseProperties (string storageAccountId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties storageAccountId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountId"><span data-ttu-id="f1356-103">自動ストレージ アカウントに使用するストレージ アカウントのリソース ID。</span><span class="sxs-lookup"><span data-stu-id="f1356-103">The resource ID of the storage account to be used for auto storage account.</span></span></param>
        <summary>
            <span data-ttu-id="f1356-104">AutoStorageBaseProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f1356-104">Initializes a new instance of the AutoStorageBaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f1356-105">取得または自動ストレージ アカウントに使用するストレージ アカウントのリソース ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="f1356-105">Gets or sets the resource ID of the storage account to be used for auto storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoStorageBaseProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f1356-106">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f1356-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1356-107">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1356-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>