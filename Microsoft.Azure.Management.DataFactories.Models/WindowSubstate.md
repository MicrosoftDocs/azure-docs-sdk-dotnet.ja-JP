<Type Name="WindowSubstate" FullName="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate">
  <TypeSignature Language="C#" Value="public static class WindowSubstate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WindowSubstate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowSubstate" />
  <TypeSignature Language="F#" Value="type WindowSubstate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf72c-101">サポートされているアクティビティのすべてのウィンドウ状態を列挙します。</span><span class="sxs-lookup"><span data-stu-id="bf72c-101">The enum for all the supported activity window states.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityResume">
      <MemberSignature Language="C#" Value="public const string ActivityResume;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ActivityResume" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ActivityResume" />
      <MemberSignature Language="VB.NET" Value="Public Const ActivityResume As String " />
      <MemberSignature Language="F#" Value="val mutable ActivityResume : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ActivityResume" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-102">アクティビティが一時停止し、再開されるまでスライスを実行することはできません。</span><span class="sxs-lookup"><span data-stu-id="bf72c-102">The activity is paused and cannot run the slices until it is resumed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Canceled">
      <MemberSignature Language="C#" Value="public const string Canceled;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Canceled" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Canceled" />
      <MemberSignature Language="VB.NET" Value="Public Const Canceled As String " />
      <MemberSignature Language="F#" Value="val mutable Canceled : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Canceled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-103">ユーザーの操作によって取り消されました。</span><span class="sxs-lookup"><span data-stu-id="bf72c-103">Canceled by user action.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeResources">
      <MemberSignature Language="C#" Value="public const string ComputeResources;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ComputeResources" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ComputeResources" />
      <MemberSignature Language="VB.NET" Value="Public Const ComputeResources As String " />
      <MemberSignature Language="F#" Value="val mutable ComputeResources : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ComputeResources" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-104">コンピューティング リソースが使用できません。</span><span class="sxs-lookup"><span data-stu-id="bf72c-104">The compute resources are not available.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrencyLimit">
      <MemberSignature Language="C#" Value="public const string ConcurrencyLimit;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ConcurrencyLimit" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ConcurrencyLimit" />
      <MemberSignature Language="VB.NET" Value="Public Const ConcurrencyLimit As String " />
      <MemberSignature Language="F#" Value="val mutable ConcurrencyLimit : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ConcurrencyLimit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-105">すべてのアクティビティ インスタンスが、他のアクティビティ ウィンドウを実行しています。</span><span class="sxs-lookup"><span data-stu-id="bf72c-105">All the activity instances are busy running other activity windows.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatasetDependencies">
      <MemberSignature Language="C#" Value="public const string DatasetDependencies;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DatasetDependencies" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.DatasetDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Const DatasetDependencies As String " />
      <MemberSignature Language="F#" Value="val mutable DatasetDependencies : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.DatasetDependencies" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-106">アップ ストリームの依存関係の準備ができていません。</span><span class="sxs-lookup"><span data-stu-id="bf72c-106">The upstream dependencies are not ready.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="public const string Retry;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Retry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Retry" />
      <MemberSignature Language="VB.NET" Value="Public Const Retry As String " />
      <MemberSignature Language="F#" Value="val mutable Retry : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Retry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-107">アクティビティの実行は再試行されます。</span><span class="sxs-lookup"><span data-stu-id="bf72c-107">The activity execution will be retried.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledTime">
      <MemberSignature Language="C#" Value="public const string ScheduledTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ScheduledTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ScheduledTime" />
      <MemberSignature Language="VB.NET" Value="Public Const ScheduledTime As String " />
      <MemberSignature Language="F#" Value="val mutable ScheduledTime : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ScheduledTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-108">実行するアクティビティの期間のスケジュールされた時刻はまだ成功していません。</span><span class="sxs-lookup"><span data-stu-id="bf72c-108">The scheduled time for the activity window to run has not yet passed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimedOut">
      <MemberSignature Language="C#" Value="public const string TimedOut;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string TimedOut" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.TimedOut" />
      <MemberSignature Language="VB.NET" Value="Public Const TimedOut As String " />
      <MemberSignature Language="F#" Value="val mutable TimedOut : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.TimedOut" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-109">実行は、アクティビティのタイムアウト時間で許可されているよりも長くかかりました。</span><span class="sxs-lookup"><span data-stu-id="bf72c-109">Execution took longer than allowed by the activity's timeout period.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validating">
      <MemberSignature Language="C#" Value="public const string Validating;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Validating" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Validating" />
      <MemberSignature Language="VB.NET" Value="Public Const Validating As String " />
      <MemberSignature Language="F#" Value="val mutable Validating : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Validating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-110">検証を実行中です。</span><span class="sxs-lookup"><span data-stu-id="bf72c-110">Validation in progress.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validation">
      <MemberSignature Language="C#" Value="public const string Validation;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Validation" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Validation" />
      <MemberSignature Language="VB.NET" Value="Public Const Validation As String " />
      <MemberSignature Language="F#" Value="val mutable Validation : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.Validation" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-111">検証が開始されていない、失敗状態にも使用できます。</span><span class="sxs-lookup"><span data-stu-id="bf72c-111">Validation has not started yet, can be used with Failed state as well.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidationRetry">
      <MemberSignature Language="C#" Value="public const string ValidationRetry;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ValidationRetry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ValidationRetry" />
      <MemberSignature Language="VB.NET" Value="Public Const ValidationRetry As String " />
      <MemberSignature Language="F#" Value="val mutable ValidationRetry : string" Usage="Microsoft.Azure.Management.DataFactories.Models.WindowSubstate.ValidationRetry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf72c-112">検証の再試行を待機しています。</span><span class="sxs-lookup"><span data-stu-id="bf72c-112">Waiting for the validation to be retried.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>