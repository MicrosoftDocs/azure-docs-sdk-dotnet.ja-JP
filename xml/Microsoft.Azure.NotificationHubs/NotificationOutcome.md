<Type Name="NotificationOutcome" FullName="Microsoft.Azure.NotificationHubs.NotificationOutcome">
  <TypeSignature Language="C#" Value="public sealed class NotificationOutcome" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NotificationOutcome extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NotificationOutcome" />
  <TypeSignature Language="F#" Value="type NotificationOutcome = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NotificationOutcome", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="08940-101">通知の成果を表します。</span><span class="sxs-lookup"><span data-stu-id="08940-101">Represents a notification outcome.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationOutcome ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationOutcome.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="08940-102"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08940-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failure">
      <MemberSignature Language="C#" Value="public long Failure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Failure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.Failure" />
      <MemberSignature Language="VB.NET" Value="Public Property Failure As Long" />
      <MemberSignature Language="F#" Value="member this.Failure : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.Failure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Failure", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08940-103">取得または結果のエラー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="08940-103">Gets or sets the failure value of the outcome.</span></span></summary>
        <value><span data-ttu-id="08940-104">結果のエラー値。</span><span class="sxs-lookup"><span data-stu-id="08940-104">The failure value of the outcome.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationId">
      <MemberSignature Language="C#" Value="public string NotificationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NotificationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationId As String" />
      <MemberSignature Language="F#" Value="member this.NotificationId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="08940-105">取得または通知 ID を設定します</span><span class="sxs-lookup"><span data-stu-id="08940-105">Gets or sets the notification ID.</span></span>
            </summary>
        <value>
            <span data-ttu-id="08940-106">通知の id。</span><span class="sxs-lookup"><span data-stu-id="08940-106">notification ID.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.RegistrationResult&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As List(Of RegistrationResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.RegistrationResult&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Results", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.RegistrationResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08940-107">取得または通知の一覧に結果の結果を設定します。</span><span class="sxs-lookup"><span data-stu-id="08940-107">Gets or sets the list of notification outcome results.</span></span></summary>
        <value><span data-ttu-id="08940-108">通知の結果の結果の一覧。</span><span class="sxs-lookup"><span data-stu-id="08940-108">The list of notification outcome results.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationOutcomeState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.NotificationOutcomeState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As NotificationOutcomeState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.NotificationHubs.NotificationOutcomeState" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationOutcomeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08940-109">取得またはこの通知の成果の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="08940-109">Gets or sets the state of this notification outcome.</span></span></summary>
        <value><span data-ttu-id="08940-110">この通知の成果の状態。</span><span class="sxs-lookup"><span data-stu-id="08940-110">The state of this notification outcome.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="public long Success { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Success" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.Success" />
      <MemberSignature Language="VB.NET" Value="Public Property Success As Long" />
      <MemberSignature Language="F#" Value="member this.Success : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.Success" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Success", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08940-111">取得または結果の成功値を設定します。</span><span class="sxs-lookup"><span data-stu-id="08940-111">Gets or sets the success value of the outcome.</span></span></summary>
        <value><span data-ttu-id="08940-112">結果の成功値。</span><span class="sxs-lookup"><span data-stu-id="08940-112">The success value of the outcome.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackingId">
      <MemberSignature Language="C#" Value="public string TrackingId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrackingId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.TrackingId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrackingId As String" />
      <MemberSignature Language="F#" Value="member this.TrackingId : string" Usage="Microsoft.Azure.NotificationHubs.NotificationOutcome.TrackingId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="08940-113">取得または設定追跡 id。</span><span class="sxs-lookup"><span data-stu-id="08940-113">Gets or sets the tracking ID.</span></span></summary>
        <value><span data-ttu-id="08940-114">追跡 id。</span><span class="sxs-lookup"><span data-stu-id="08940-114">The tracking ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>