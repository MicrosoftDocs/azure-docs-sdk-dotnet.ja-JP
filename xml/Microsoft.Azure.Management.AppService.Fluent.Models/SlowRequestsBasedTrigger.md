<Type Name="SlowRequestsBasedTrigger" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger">
  <TypeSignature Language="C#" Value="public class SlowRequestsBasedTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SlowRequestsBasedTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class SlowRequestsBasedTrigger" />
  <TypeSignature Language="F#" Value="type SlowRequestsBasedTrigger = class" />
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
            <span data-ttu-id="35782-101">要求の実行時刻に基づいてトリガーします。</span><span class="sxs-lookup"><span data-stu-id="35782-101">Trigger based on request execution time.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlowRequestsBasedTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35782-102">SlowRequestsBasedTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35782-102">Initializes a new instance of the SlowRequestsBasedTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SlowRequestsBasedTrigger (string timeTaken = null, Nullable&lt;int&gt; count = null, string timeInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeTaken, valuetype System.Nullable`1&lt;int32&gt; count, string timeInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.#ctor(System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeTaken As String = null, Optional count As Nullable(Of Integer) = null, Optional timeInterval As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger : string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger (timeTaken, count, timeInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeTaken" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeInterval" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="timeTaken"><span data-ttu-id="35782-103">かかった時間です。</span><span class="sxs-lookup"><span data-stu-id="35782-103">Time taken.</span></span></param>
        <param name="count"><span data-ttu-id="35782-104">カウントです。</span><span class="sxs-lookup"><span data-stu-id="35782-104">Count.</span></span></param>
        <param name="timeInterval"><span data-ttu-id="35782-105">時間間隔。</span><span class="sxs-lookup"><span data-stu-id="35782-105">Time interval.</span></span></param>
        <summary>
            <span data-ttu-id="35782-106">SlowRequestsBasedTrigger クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35782-106">Initializes a new instance of the SlowRequestsBasedTrigger class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35782-107">取得または数を設定します。</span><span class="sxs-lookup"><span data-stu-id="35782-107">Gets or sets count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeInterval">
      <MemberSignature Language="C#" Value="public string TimeInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.TimeInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeInterval As String" />
      <MemberSignature Language="F#" Value="member this.TimeInterval : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.TimeInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35782-108">取得または時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="35782-108">Gets or sets time interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeTaken">
      <MemberSignature Language="C#" Value="public string TimeTaken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeTaken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.TimeTaken" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeTaken As String" />
      <MemberSignature Language="F#" Value="member this.TimeTaken : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SlowRequestsBasedTrigger.TimeTaken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeTaken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35782-109">取得または設定にかかった時間。</span><span class="sxs-lookup"><span data-stu-id="35782-109">Gets or sets time taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>