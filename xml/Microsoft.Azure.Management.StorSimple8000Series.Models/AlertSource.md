<Type Name="AlertSource" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource">
  <TypeSignature Language="C#" Value="public class AlertSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertSource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertSource" />
  <TypeSignature Language="F#" Value="type AlertSource = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="19499-101">アラートが発生したソースの詳細</span><span class="sxs-lookup"><span data-stu-id="19499-101">The source details at which the alert was raised</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="19499-102">AlertSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="19499-102">Initializes a new instance of the AlertSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertSource (string name = null, string timeZone = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; alertSourceType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string timeZone, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; alertSourceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional timeZone As String = null, Optional alertSourceType As Nullable(Of AlertSourceType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource : string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource (name, timeZone, alertSourceType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="alertSourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="19499-103">ソースの名前</span><span class="sxs-lookup"><span data-stu-id="19499-103">The name of the source</span></span></param>
        <param name="timeZone"><span data-ttu-id="19499-104">ソースのタイム ゾーン</span><span class="sxs-lookup"><span data-stu-id="19499-104">The time zone of the source</span></span></param>
        <param name="alertSourceType"><span data-ttu-id="19499-105">アラートのソースの種類。</span><span class="sxs-lookup"><span data-stu-id="19499-105">The source type of the alert.</span></span>
            <span data-ttu-id="19499-106">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="19499-106">Possible values include: 'Resource', 'Device'</span></span></param>
        <summary>
            <span data-ttu-id="19499-107">AlertSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="19499-107">Initializes a new instance of the AlertSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertSourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; AlertSourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; AlertSourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.AlertSourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property AlertSourceType As Nullable(Of AlertSourceType)" />
      <MemberSignature Language="F#" Value="member this.AlertSourceType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.AlertSourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="alertSourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19499-108">取得またはアラートのソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="19499-108">Gets or sets the source type of the alert.</span></span> <span data-ttu-id="19499-109">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="19499-109">Possible values include: 'Resource', 'Device'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19499-110">取得または設定のソースの名前</span><span class="sxs-lookup"><span data-stu-id="19499-110">Gets or sets the name of the source</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19499-111">取得または設定のソース タイム ゾーン</span><span class="sxs-lookup"><span data-stu-id="19499-111">Gets or sets the time zone of the source</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>