<Type Name="AzureTableStorageApplicationLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class AzureTableStorageApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableStorageApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableStorageApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type AzureTableStorageApplicationLogsConfig = class" />
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
            <span data-ttu-id="e633b-101">Azure テーブル ストレージの構成にアプリケーションを記録します。</span><span class="sxs-lookup"><span data-stu-id="e633b-101">Application logs to Azure table storage configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableStorageApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e633b-102">AzureTableStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e633b-102">Initializes a new instance of the AzureTableStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableStorageApplicationLogsConfig (string sasUrl, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasUrl, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasUrl As String, Optional level As Nullable(Of LogLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig : string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig (sasUrl, level)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasUrl" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="sasUrl"><span data-ttu-id="e633b-103">追加/クエリ/削除アクセス許可を持つ Azure テーブルの SAS URL。</span><span class="sxs-lookup"><span data-stu-id="e633b-103">SAS URL to an Azure table with add/query/delete permissions.</span></span></param>
        <param name="level"><span data-ttu-id="e633b-104">ログ レベル。</span><span class="sxs-lookup"><span data-stu-id="e633b-104">Log level.</span></span> <span data-ttu-id="e633b-105">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="e633b-105">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span></param>
        <summary>
            <span data-ttu-id="e633b-106">AzureTableStorageApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e633b-106">Initializes a new instance of the AzureTableStorageApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e633b-107">取得またはログ レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e633b-107">Gets or sets log level.</span></span> <span data-ttu-id="e633b-108">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="e633b-108">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasUrl">
      <MemberSignature Language="C#" Value="public string SasUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SasUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.SasUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SasUrl As String" />
      <MemberSignature Language="F#" Value="member this.SasUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.SasUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sasUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e633b-109">取得または SAS URL を追加/クエリ/削除アクセス許可を持つ Azure テーブルに設定します。</span><span class="sxs-lookup"><span data-stu-id="e633b-109">Gets or sets SAS URL to an Azure table with add/query/delete permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AzureTableStorageApplicationLogsConfig.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureTableStorageApplicationLogsConfig.Validate " />
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
            <span data-ttu-id="e633b-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e633b-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e633b-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e633b-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>