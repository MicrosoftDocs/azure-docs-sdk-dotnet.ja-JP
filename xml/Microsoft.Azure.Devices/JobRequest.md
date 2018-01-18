<Type Name="JobRequest" FullName="Microsoft.Azure.Devices.JobRequest">
  <TypeSignature Language="C#" Value="public class JobRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class JobRequest" />
  <TypeSignature Language="F#" Value="type JobRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fb0d0-101">ジョブの入力</span><span class="sxs-lookup"><span data-stu-id="fb0d0-101">Job input</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudToDeviceMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.CloudToDeviceMethod CloudToDeviceMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.CloudToDeviceMethod CloudToDeviceMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.CloudToDeviceMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudToDeviceMethod As CloudToDeviceMethod" />
      <MemberSignature Language="F#" Value="member this.CloudToDeviceMethod : Microsoft.Azure.Devices.CloudToDeviceMethod with get, set" Usage="Microsoft.Azure.Devices.JobRequest.CloudToDeviceMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudToDeviceMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.CloudToDeviceMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-102">JobType が cloudToDeviceMethod がかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-102">Required if jobType is cloudToDeviceMethod.</span></span>
            <span data-ttu-id="fb0d0-103">メソッドの型およびパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-103">The method type and parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Devices.JobRequest.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-104">ジョブの識別子</span><span class="sxs-lookup"><span data-stu-id="fb0d0-104">Job identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.JobType JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.JobType JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As JobType" />
      <MemberSignature Language="F#" Value="member this.JobType : Microsoft.Azure.Devices.JobType with get, set" Usage="Microsoft.Azure.Devices.JobRequest.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-105">必須。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-105">Required.</span></span>
            <span data-ttu-id="fb0d0-106">実行するジョブの種類。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-106">The type of job to execute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxExecutionTimeInSeconds">
      <MemberSignature Language="C#" Value="public long MaxExecutionTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxExecutionTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.MaxExecutionTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxExecutionTimeInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.MaxExecutionTimeInSeconds : int64 with get, set" Usage="Microsoft.Azure.Devices.JobRequest.MaxExecutionTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(DefaultValueHandling=Newtonsoft.Json.DefaultValueHandling.IgnoreAndPopulate, PropertyName="maxExecutionTimeInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-107">最大実行時間 (秒) (ttl 期間)</span><span class="sxs-lookup"><span data-stu-id="fb0d0-107">Max execution time in seconds (ttl duration)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryCondition">
      <MemberSignature Language="C#" Value="public string QueryCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueryCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.QueryCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryCondition As String" />
      <MemberSignature Language="F#" Value="member this.QueryCondition : string with get, set" Usage="Microsoft.Azure.Devices.JobRequest.QueryCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryCondition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-108">JobType が updateTwin または cloudToDeviceMethod かどうか必要です。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-108">Required if jobType is updateTwin or cloudToDeviceMethod.</span></span>
            <span data-ttu-id="fb0d0-109">デバイスを取得するクエリで、ジョブを実行するデバイスの条件</span><span class="sxs-lookup"><span data-stu-id="fb0d0-109">Condition for device query to get devices to execute the job on</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Devices.JobRequest.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.IsoDateTimeConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-110">ISO 8601 の日付/時刻、ジョブを開始するには</span><span class="sxs-lookup"><span data-stu-id="fb0d0-110">ISO 8601 date time to start the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Shared.Twin UpdateTwin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Shared.Twin UpdateTwin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.JobRequest.UpdateTwin" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateTwin As Twin" />
      <MemberSignature Language="F#" Value="member this.UpdateTwin : Microsoft.Azure.Devices.Shared.Twin with get, set" Usage="Microsoft.Azure.Devices.JobRequest.UpdateTwin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updateTwin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Shared.Twin</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb0d0-111">JobType が updateTwin がかどうかに必要です。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-111">Required if jobType is updateTwin.</span></span>
            <span data-ttu-id="fb0d0-112">更新ツイン タグと必要なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fb0d0-112">The Update Twin tags and desired properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>