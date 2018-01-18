<Type Name="ExportDevicesRequest" FullName="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest">
  <TypeSignature Language="C#" Value="public class ExportDevicesRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportDevicesRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportDevicesRequest" />
  <TypeSignature Language="F#" Value="type ExportDevicesRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d3bbf-101">パラメーターを提供するすべてのデバイスが IoT hub でのエクスポートを要求するときに使用します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-101">Use to provide parameters when requesting an export of all devices in the IoT hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportDevicesRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3bbf-102">ExportDevicesRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-102">Initializes a new instance of the ExportDevicesRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportDevicesRequest (string exportBlobContainerUri, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exportBlobContainerUri, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exportBlobContainerUri As String, excludeKeys As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest : string * bool -&gt; Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" Usage="new Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest (exportBlobContainerUri, excludeKeys)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"><span data-ttu-id="d3bbf-103">エクスポート blob コンテナーへの URI。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-103">The export blob container URI.</span></span></param>
        <param name="excludeKeys"><span data-ttu-id="d3bbf-104">キーをエクスポート中に除外するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-104">The value indicating whether keys should be excluded during export.</span></span></param>
        <summary>
            <span data-ttu-id="d3bbf-105">ExportDevicesRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-105">Initializes a new instance of the ExportDevicesRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeKeys">
      <MemberSignature Language="C#" Value="public bool ExcludeKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExcludeKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeKeys As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeKeys : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExcludeKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ExcludeKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3bbf-106">取得またはキーをエクスポート中に除外するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-106">Gets or sets the value indicating whether keys should be excluded during export.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportBlobContainerUri">
      <MemberSignature Language="C#" Value="public string ExportBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExportBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExportBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ExportBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.ExportBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExportBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ExportBlobContainerUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3bbf-107">取得またはエクスポート blob コンテナーへの URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-107">Gets or sets the export blob container URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exportDevicesRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3bbf-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3bbf-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3bbf-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>