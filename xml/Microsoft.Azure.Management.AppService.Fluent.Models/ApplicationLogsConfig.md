<Type Name="ApplicationLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class ApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type ApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8cd52-101">アプリケーションでは、構成を記録します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-101">Application logs configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8cd52-102">ApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-102">Initializes a new instance of the ApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationLogsConfig (Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig fileSystem = null, Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig azureTableStorage = null, Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig azureBlobStorage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig fileSystem, class Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig azureTableStorage, class Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig azureBlobStorage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.#ctor(Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig,Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig,Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fileSystem As FileSystemApplicationLogsConfig = null, Optional azureTableStorage As AzureTableStorageApplicationLogsConfig = null, Optional azureBlobStorage As AzureBlobStorageApplicationLogsConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig : Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig * Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig * Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig (fileSystem, azureTableStorage, azureBlobStorage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fileSystem" Type="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig" />
        <Parameter Name="azureTableStorage" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig" />
        <Parameter Name="azureBlobStorage" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig" />
      </Parameters>
      <Docs>
        <param name="fileSystem"><span data-ttu-id="8cd52-103">ファイル システムの構成にアプリケーションを記録します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-103">Application logs to file system configuration.</span></span></param>
        <param name="azureTableStorage"><span data-ttu-id="8cd52-104">Azure テーブル ストレージの構成にアプリケーションを記録します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-104">Application logs to azure table storage configuration.</span></span></param>
        <param name="azureBlobStorage"><span data-ttu-id="8cd52-105">アプリケーションは、blob ストレージの構成を記録します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-105">Application logs to blob storage configuration.</span></span></param>
        <summary>
            <span data-ttu-id="8cd52-106">ApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-106">Initializes a new instance of the ApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig AzureBlobStorage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig AzureBlobStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.AzureBlobStorage" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureBlobStorage As AzureBlobStorageApplicationLogsConfig" />
      <MemberSignature Language="F#" Value="member this.AzureBlobStorage : Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.AzureBlobStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureBlobStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AzureBlobStorageApplicationLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cd52-107">取得またはアプリケーションのログを blob ストレージの構成に設定します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-107">Gets or sets application logs to blob storage configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig AzureTableStorage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig AzureTableStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.AzureTableStorage" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableStorage As AzureTableStorageApplicationLogsConfig" />
      <MemberSignature Language="F#" Value="member this.AzureTableStorage : Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.AzureTableStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cd52-108">取得またはアプリケーションのログを azure テーブル ストレージの構成に設定します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-108">Gets or sets application logs to azure table storage configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig FileSystem { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig FileSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.FileSystem" />
      <MemberSignature Language="VB.NET" Value="Public Property FileSystem As FileSystemApplicationLogsConfig" />
      <MemberSignature Language="F#" Value="member this.FileSystem : Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.FileSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cd52-109">取得またはアプリケーションのログをファイル システムの構成に設定します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-109">Gets or sets application logs to file system configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ApplicationLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationLogsConfig.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8cd52-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8cd52-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8cd52-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8cd52-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>