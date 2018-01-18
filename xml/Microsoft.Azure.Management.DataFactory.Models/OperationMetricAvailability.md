<Type Name="OperationMetricAvailability" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability">
  <TypeSignature Language="C#" Value="public class OperationMetricAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationMetricAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationMetricAvailability" />
  <TypeSignature Language="F#" Value="type OperationMetricAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="617a3-101">どのくらいの頻度が定義されたメトリックのデータができるようになります。</span><span class="sxs-lookup"><span data-stu-id="617a3-101">Defines how often data for a metric becomes available.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="617a3-102">OperationMetricAvailability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="617a3-102">Initializes a new instance of the OperationMetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationMetricAvailability (string timeGrain = null, string blobDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeGrain, string blobDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeGrain As String = null, Optional blobDuration As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability : string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability (timeGrain, blobDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="blobDuration" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeGrain"><span data-ttu-id="617a3-103">メトリックの粒度。</span><span class="sxs-lookup"><span data-stu-id="617a3-103">The granularity for the metric.</span></span></param>
        <param name="blobDuration"><span data-ttu-id="617a3-104">顧客のストレージ アカウントの 1 時間あたりに作成された blob です。</span><span class="sxs-lookup"><span data-stu-id="617a3-104">Blob created in the customer storage account, per hour.</span></span></param>
        <summary>
            <span data-ttu-id="617a3-105">OperationMetricAvailability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="617a3-105">Initializes a new instance of the OperationMetricAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobDuration">
      <MemberSignature Language="C#" Value="public string BlobDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.BlobDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobDuration As String" />
      <MemberSignature Language="F#" Value="member this.BlobDuration : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.BlobDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="617a3-106">取得または顧客のストレージ アカウントの 1 時間あたりに作成された blob を設定します。</span><span class="sxs-lookup"><span data-stu-id="617a3-106">Gets or sets blob created in the customer storage account, per hour.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationMetricAvailability.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="617a3-107">取得またはメトリックの粒度を設定します。</span><span class="sxs-lookup"><span data-stu-id="617a3-107">Gets or sets the granularity for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>