<Type Name="Incident" FullName="Microsoft.Azure.Management.Monitor.Management.Models.Incident">
  <TypeSignature Language="C#" Value="public class Incident" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Incident extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.Incident" />
  <TypeSignature Language="VB.NET" Value="Public Class Incident" />
  <TypeSignature Language="F#" Value="type Incident = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="31c92-101">アラートのインシデントでは、アラート ルールのアクティブ化の状態を示します。</span><span class="sxs-lookup"><span data-stu-id="31c92-101">An alert incident indicates the activation status of an alert rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Incident ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Incident.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="31c92-102">インシデントのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="31c92-102">Initializes a new instance of the Incident class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Incident (string name = null, string ruleName = null, Nullable&lt;bool&gt; isActive = null, Nullable&lt;DateTime&gt; activatedTime = null, Nullable&lt;DateTime&gt; resolvedTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string ruleName, valuetype System.Nullable`1&lt;bool&gt; isActive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; activatedTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; resolvedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.Incident.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional ruleName As String = null, Optional isActive As Nullable(Of Boolean) = null, Optional activatedTime As Nullable(Of DateTime) = null, Optional resolvedTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.Incident : string * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.Incident" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.Incident (name, ruleName, isActive, activatedTime, resolvedTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="isActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="activatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resolvedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="31c92-103">インシデントの名前です。</span><span class="sxs-lookup"><span data-stu-id="31c92-103">Incident name.</span></span></param>
        <param name="ruleName"><span data-ttu-id="31c92-104">インシデントに関連付けられている規則の名前。</span><span class="sxs-lookup"><span data-stu-id="31c92-104">Rule name that is associated with the incident.</span></span></param>
        <param name="isActive"><span data-ttu-id="31c92-105">インシデントがアクティブまたは解決済みかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="31c92-105">A boolean to indicate whether the incident is active or resolved.</span></span></param>
        <param name="activatedTime"><span data-ttu-id="31c92-106">インシデントが ISO8601 の形式でアクティブ化時刻。</span><span class="sxs-lookup"><span data-stu-id="31c92-106">The time at which the incident was activated in ISO8601 format.</span></span></param>
        <param name="resolvedTime"><span data-ttu-id="31c92-107">ISO8601 の形式で、インシデントが解決される時刻。</span><span class="sxs-lookup"><span data-stu-id="31c92-107">The time at which the incident was resolved in ISO8601 format.</span></span> <span data-ttu-id="31c92-108">Null の場合、インシデントがアクティブであることを意味します。</span><span class="sxs-lookup"><span data-stu-id="31c92-108">If null, it means the incident is still active.</span></span></param>
        <summary>
            <span data-ttu-id="31c92-109">インシデントのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="31c92-109">Initializes a new instance of the Incident class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ActivatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ActivatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.ActivatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ActivatedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.ActivatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31c92-110">インシデントが ISO8601 の形式でアクティブ化時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="31c92-110">Gets the time at which the incident was activated in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsActive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.IsActive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsActive : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.IsActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31c92-111">インシデントがアクティブまたは解決済みかどうかを示すブール値を取得します。</span><span class="sxs-lookup"><span data-stu-id="31c92-111">Gets a boolean to indicate whether the incident is active or resolved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="31c92-112">インシデントの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="31c92-112">Gets incident name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ResolvedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ResolvedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.ResolvedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResolvedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ResolvedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.ResolvedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolvedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31c92-113">ISO8601 の形式で解決されたインシデントを取得します。</span><span class="sxs-lookup"><span data-stu-id="31c92-113">Gets the time at which the incident was resolved in ISO8601 format.</span></span>
            <span data-ttu-id="31c92-114">Null の場合、インシデントがアクティブであることを意味します。</span><span class="sxs-lookup"><span data-stu-id="31c92-114">If null, it means the incident is still active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleName">
      <MemberSignature Language="C#" Value="public string RuleName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.Incident.RuleName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuleName As String" />
      <MemberSignature Language="F#" Value="member this.RuleName : string" Usage="Microsoft.Azure.Management.Monitor.Management.Models.Incident.RuleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="31c92-115">インシデントに関連付けられているルールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="31c92-115">Gets rule name that is associated with the incident.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>