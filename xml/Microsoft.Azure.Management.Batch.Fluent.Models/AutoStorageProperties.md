<Type Name="AutoStorageProperties" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties">
  <TypeSignature Language="C#" Value="public class AutoStorageProperties : Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoStorageProperties extends Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoStorageProperties&#xA;Inherits AutoStorageBaseProperties" />
  <TypeSignature Language="F#" Value="type AutoStorageProperties = class&#xA;    inherit AutoStorageBaseProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ffdfe-101">Batch アカウントに関連付けられている自動ストレージ アカウントに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-101">Contains information about the auto storage account associated with a Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ffdfe-102">AutoStorageProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-102">Initializes a new instance of the AutoStorageProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageProperties (string storageAccountId, DateTime lastKeySync);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountId, valuetype System.DateTime lastKeySync) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountId As String, lastKeySync As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties : string * DateTime -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties (storageAccountId, lastKeySync)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="lastKeySync" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="storageAccountId"><span data-ttu-id="ffdfe-103">自動ストレージ アカウントに使用するストレージ アカウントのリソース ID。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-103">The resource ID of the storage account to be used for auto storage account.</span></span></param>
        <param name="lastKeySync"><span data-ttu-id="ffdfe-104">どの記憶域のキーが最後に同期された Batch アカウントの UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-104">The UTC time at which storage keys were last synchronized with the Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="ffdfe-105">AutoStorageProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-105">Initializes a new instance of the AutoStorageProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastKeySync">
      <MemberSignature Language="C#" Value="public DateTime LastKeySync { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastKeySync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties.LastKeySync" />
      <MemberSignature Language="VB.NET" Value="Public Property LastKeySync As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastKeySync : DateTime with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties.LastKeySync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastKeySync")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ffdfe-106">取得または設定を記憶域のキーが最後に同期されたバッチ アカウントを使用して UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-106">Gets or sets the UTC time at which storage keys were last synchronized with the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="autoStorageProperties.Validate " />
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
            <span data-ttu-id="ffdfe-107">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-107">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ffdfe-108">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ffdfe-108">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>