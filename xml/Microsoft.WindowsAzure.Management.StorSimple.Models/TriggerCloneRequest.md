<Type Name="TriggerCloneRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest">
  <TypeSignature Language="C#" Value="public class TriggerCloneRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggerCloneRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggerCloneRequest" />
  <TypeSignature Language="F#" Value="type TriggerCloneRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="efe2f-101">このクラスを表す複製要求の詳細</span><span class="sxs-lookup"><span data-stu-id="efe2f-101">This class respresents the details for clone request</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerCloneRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-102">TriggerCloneRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="efe2f-102">Initializes a new instance of the TriggerCloneRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSetId">
      <MemberSignature Language="C#" Value="public string BackupSetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupSetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.BackupSetId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSetId As String" />
      <MemberSignature Language="F#" Value="member this.BackupSetId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.BackupSetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-103">必須。</span><span class="sxs-lookup"><span data-stu-id="efe2f-103">Required.</span></span> <span data-ttu-id="efe2f-104">バックアップ セットの一部では、現在のスナップショットの id</span><span class="sxs-lookup"><span data-stu-id="efe2f-104">The id of the backup set which the current snapshot is part of</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnWorkflowId">
      <MemberSignature Language="C#" Value="public bool ReturnWorkflowId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReturnWorkflowId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.ReturnWorkflowId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnWorkflowId As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReturnWorkflowId : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.ReturnWorkflowId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="efe2f-105">Optional.</span></span> <span data-ttu-id="efe2f-106">メソッドが、workflowId を返すかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="efe2f-106">Determines whether or not the method will return the workflowId</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot SourceSnapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot SourceSnapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.SourceSnapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceSnapshot As Snapshot" />
      <MemberSignature Language="F#" Value="member this.SourceSnapshot : Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.SourceSnapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-107">必須。</span><span class="sxs-lookup"><span data-stu-id="efe2f-107">Required.</span></span> <span data-ttu-id="efe2f-108">クローンを作成するのには、バックアップからのスナップショット</span><span class="sxs-lookup"><span data-stu-id="efe2f-108">Snapshot from a backup which is to be cloned</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetACRIdList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TargetACRIdList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TargetACRIdList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRIdList" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetACRIdList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TargetACRIdList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRIdList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="efe2f-109">Optional.</span></span> <span data-ttu-id="efe2f-110">複製されたボリュームに追加する既存のアクセス制御レコードの一覧</span><span class="sxs-lookup"><span data-stu-id="efe2f-110">List of existing access control records to add to the cloned volume</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetACRList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; TargetACRList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; TargetACRList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRList" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetACRList As IList(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="member this.TargetACRList : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="efe2f-111">Optional.</span></span> <span data-ttu-id="efe2f-112">複製されたボリュームに追加する新しいアクセス制御レコードの一覧</span><span class="sxs-lookup"><span data-stu-id="efe2f-112">List of new access control records to add to the cloned volume</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDeviceId">
      <MemberSignature Language="C#" Value="public string TargetDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDeviceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-113">必須。</span><span class="sxs-lookup"><span data-stu-id="efe2f-113">Required.</span></span> <span data-ttu-id="efe2f-114">ターゲット デバイス id にボリュームを複製する必要があります。</span><span class="sxs-lookup"><span data-stu-id="efe2f-114">The target device id, where the volume must be cloned to</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetVolName">
      <MemberSignature Language="C#" Value="public string TargetVolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetVolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetVolName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetVolName As String" />
      <MemberSignature Language="F#" Value="member this.TargetVolName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetVolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="efe2f-115">必須。</span><span class="sxs-lookup"><span data-stu-id="efe2f-115">Required.</span></span> <span data-ttu-id="efe2f-116">複製されたボリュームの名前</span><span class="sxs-lookup"><span data-stu-id="efe2f-116">Name of the cloned volume</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>