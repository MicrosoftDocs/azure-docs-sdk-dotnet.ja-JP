<Type Name="BatchErrorMessages" FullName="Microsoft.Azure.Batch.BatchErrorMessages">
  <TypeSignature Language="C#" Value="public class BatchErrorMessages" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchErrorMessages extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchErrorMessages" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchErrorMessages" />
  <TypeSignature Language="F#" Value="type BatchErrorMessages = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerNonUserCode</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
               <span data-ttu-id="a85ec-101">ローカライズされた文字列などを検索するための厳密に型指定されたリソース クラスです。</span><span class="sxs-lookup"><span data-stu-id="a85ec-101">A strongly-typed resource class, for looking up localized strings, etc.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTaskCollectionTerminated">
      <MemberSignature Language="C#" Value="public static string AddTaskCollectionTerminated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string AddTaskCollectionTerminated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.AddTaskCollectionTerminated" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property AddTaskCollectionTerminated As String" />
      <MemberSignature Language="F#" Value="member this.AddTaskCollectionTerminated : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.AddTaskCollectionTerminated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-102">予期しない状態コードで失敗しました。 タスクの追加に類似したローカライズされた文字列を検索します。</span><span class="sxs-lookup"><span data-stu-id="a85ec-102">Looks up a localized string similar to Addition of a task failed with unexpected status code.</span></span> <span data-ttu-id="a85ec-103">詳細: {0}。</span><span class="sxs-lookup"><span data-stu-id="a85ec-103">Details: {0}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskResultActionUnretryableFailure">
      <MemberSignature Language="C#" Value="public static string AddTaskResultActionUnretryableFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string AddTaskResultActionUnretryableFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.AddTaskResultActionUnretryableFailure" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property AddTaskResultActionUnretryableFailure As String" />
      <MemberSignature Language="F#" Value="member this.AddTaskResultActionUnretryableFailure : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.AddTaskResultActionUnretryableFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-104">タスク {0} に類似したローカライズされた文字列の検索には、AddTaskResultAction.UnretryableFailure が報告されました。</span><span class="sxs-lookup"><span data-stu-id="a85ec-104">Looks up a localized string similar to Task {0} reported AddTaskResultAction.UnretryableFailure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchClientIsClosed">
      <MemberSignature Language="C#" Value="public static string BatchClientIsClosed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string BatchClientIsClosed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.BatchClientIsClosed" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property BatchClientIsClosed As String" />
      <MemberSignature Language="F#" Value="member this.BatchClientIsClosed : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.BatchClientIsClosed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-105">Closed 状態にある BatchClient のインスタンスを使用しようとしてに類似したローカライズされた文字列を検索しました。</span><span class="sxs-lookup"><span data-stu-id="a85ec-105">Looks up a localized string similar to An attempt was made to use an instance of BatchClient that is in the closed state.</span></span>  <span data-ttu-id="a85ec-106">インスタンスをバッチ サービスそれ以降の呼び出しがない可能です。</span><span class="sxs-lookup"><span data-stu-id="a85ec-106">No further calls to the Batch Service can be made with that instance.</span></span>  <span data-ttu-id="a85ec-107">これは、インスタンスが明示的に終了した場合、または BatchClient.Dispose() メソッドが呼び出された場合に発生することができます.</span><span class="sxs-lookup"><span data-stu-id="a85ec-107">This can happen if the instance was explicitly closed or if the BatchClient.Dispose() method was called..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchRequestCannotBeModified">
      <MemberSignature Language="C#" Value="public static string BatchRequestCannotBeModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string BatchRequestCannotBeModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.BatchRequestCannotBeModified" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property BatchRequestCannotBeModified As String" />
      <MemberSignature Language="F#" Value="member this.BatchRequestCannotBeModified : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.BatchRequestCannotBeModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-108">この BatchRequest に類似したローカライズされた文字列を検索では、実行が開始され、変更はできません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-108">Looks up a localized string similar to This BatchRequest has started executing and can no longer be modified..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CannotPatchNullValue">
      <MemberSignature Language="C#" Value="public static string CannotPatchNullValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string CannotPatchNullValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.CannotPatchNullValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property CannotPatchNullValue As String" />
      <MemberSignature Language="F#" Value="member this.CannotPatchNullValue : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.CannotPatchNullValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-109">CommitChanges 操作を呼び出す場合、値は null に類似したローカライズされた文字列を検索を指定することはできません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-109">Looks up a localized string similar to A value of null cannot be specified when invoking the CommitChanges operation..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanOnlyBeRunOnceFailure">
      <MemberSignature Language="C#" Value="public static string CanOnlyBeRunOnceFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string CanOnlyBeRunOnceFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.CanOnlyBeRunOnceFailure" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property CanOnlyBeRunOnceFailure As String" />
      <MemberSignature Language="F#" Value="member this.CanOnlyBeRunOnceFailure : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.CanOnlyBeRunOnceFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-110">{0} に類似したローカライズされた文字列の検索は一度だけ実行されます.</span><span class="sxs-lookup"><span data-stu-id="a85ec-110">Looks up a localized string similar to {0} can only be run once..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionMustNotContainNull">
      <MemberSignature Language="C#" Value="public static string CollectionMustNotContainNull { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string CollectionMustNotContainNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.CollectionMustNotContainNull" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property CollectionMustNotContainNull As String" />
      <MemberSignature Language="F#" Value="member this.CollectionMustNotContainNull : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.CollectionMustNotContainNull" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-111">コレクションに含まれている項目に類似したローカライズされた文字列の検索を null にするにはできません。</span><span class="sxs-lookup"><span data-stu-id="a85ec-111">Looks up a localized string similar to Items contained in collection must not be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Culture">
      <MemberSignature Language="C#" Value="public static System.Globalization.CultureInfo Culture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property class System.Globalization.CultureInfo Culture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.Culture" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property Culture As CultureInfo" />
      <MemberSignature Language="F#" Value="member this.Culture : System.Globalization.CultureInfo with get, set" Usage="Microsoft.Azure.Batch.BatchErrorMessages.Culture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Advanced)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Globalization.CultureInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-112">この厳密に型指定されたリソース クラスを使用するすべてのリソース検索を現在のスレッドの CurrentUICulture プロパティをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="a85ec-112">Overrides the current thread's CurrentUICulture property for all resource lookups using this strongly typed resource class.</span></span>
               </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralBehaviorMissing">
      <MemberSignature Language="C#" Value="public static string GeneralBehaviorMissing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string GeneralBehaviorMissing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.GeneralBehaviorMissing" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property GeneralBehaviorMissing As String" />
      <MemberSignature Language="F#" Value="member this.GeneralBehaviorMissing : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.GeneralBehaviorMissing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-113">類似したローカライズされた文字列は {0} 型の少なくとも 1 つの動作が必要です。</span><span class="sxs-lookup"><span data-stu-id="a85ec-113">Looks up a localized string similar to Must have at least one behavior of type {0}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralObjectInInvalidState">
      <MemberSignature Language="C#" Value="public static string GeneralObjectInInvalidState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string GeneralObjectInInvalidState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.GeneralObjectInInvalidState" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property GeneralObjectInInvalidState As String" />
      <MemberSignature Language="F#" Value="member this.GeneralObjectInInvalidState : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.GeneralObjectInInvalidState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-114">このオブジェクトに類似したローカライズされた文字列の検索は無効な状態です。</span><span class="sxs-lookup"><span data-stu-id="a85ec-114">Looks up a localized string similar to This object is in an invalid state.</span></span>  <span data-ttu-id="a85ec-115">書き込みアクセスが許可されていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-115">Write access is not allowed..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralSimultaneousCommitsForbidden">
      <MemberSignature Language="C#" Value="public static string GeneralSimultaneousCommitsForbidden { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string GeneralSimultaneousCommitsForbidden" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.GeneralSimultaneousCommitsForbidden" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property GeneralSimultaneousCommitsForbidden As String" />
      <MemberSignature Language="F#" Value="member this.GeneralSimultaneousCommitsForbidden : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.GeneralSimultaneousCommitsForbidden" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-116">同時コミット演算子に類似したローカライズされた文字列の検索が許可されていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-116">Looks up a localized string similar to Simultaneous Commit operators are forbidden..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncorrectTypeReturned">
      <MemberSignature Language="C#" Value="public static string IncorrectTypeReturned { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string IncorrectTypeReturned" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.IncorrectTypeReturned" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property IncorrectTypeReturned As String" />
      <MemberSignature Language="F#" Value="member this.IncorrectTypeReturned : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.IncorrectTypeReturned" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-117">返される型が正しくないに類似したローカライズされた文字列を検索.</span><span class="sxs-lookup"><span data-stu-id="a85ec-117">Looks up a localized string similar to Incorrect type returned..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorInstancesMustHaveSameServerSideParent">
      <MemberSignature Language="C#" Value="public static string MonitorInstancesMustHaveSameServerSideParent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string MonitorInstancesMustHaveSameServerSideParent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.MonitorInstancesMustHaveSameServerSideParent" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MonitorInstancesMustHaveSameServerSideParent As String" />
      <MemberSignature Language="F#" Value="member this.MonitorInstancesMustHaveSameServerSideParent : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.MonitorInstancesMustHaveSameServerSideParent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-118">モニターに類似したローカライズされた文字列の検索には、同じサーバー側の親を持つすべてのインスタンスが必要です.</span><span class="sxs-lookup"><span data-stu-id="a85ec-118">Looks up a localized string similar to Monitor requires all instances to have the same server-side parent..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultipleParallelRequestsHitUnexpectedErrors">
      <MemberSignature Language="C#" Value="public static string MultipleParallelRequestsHitUnexpectedErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string MultipleParallelRequestsHitUnexpectedErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.MultipleParallelRequestsHitUnexpectedErrors" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MultipleParallelRequestsHitUnexpectedErrors As String" />
      <MemberSignature Language="F#" Value="member this.MultipleParallelRequestsHitUnexpectedErrors : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.MultipleParallelRequestsHitUnexpectedErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-119">Azure Batch サービスは失敗を 1 つまたは複数の要求に類似したローカライズされた文字列を検索.</span><span class="sxs-lookup"><span data-stu-id="a85ec-119">Looks up a localized string similar to One or more requests to the Azure Batch service failed..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ODataMonitorTimedOut">
      <MemberSignature Language="C#" Value="public static string ODataMonitorTimedOut { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string ODataMonitorTimedOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.ODataMonitorTimedOut" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property ODataMonitorTimedOut As String" />
      <MemberSignature Language="F#" Value="member this.ODataMonitorTimedOut : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.ODataMonitorTimedOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-120">{0} 後のリソースを待機中に定刻に類似したローカライズされた文字列を検索.</span><span class="sxs-lookup"><span data-stu-id="a85ec-120">Looks up a localized string similar to Timed out waiting for resources after {0}..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationForbiddenOnBoundObjects">
      <MemberSignature Language="C#" Value="public static string OperationForbiddenOnBoundObjects { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string OperationForbiddenOnBoundObjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.OperationForbiddenOnBoundObjects" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property OperationForbiddenOnBoundObjects As String" />
      <MemberSignature Language="F#" Value="member this.OperationForbiddenOnBoundObjects : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.OperationForbiddenOnBoundObjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-121">この操作に類似したローカライズされた文字列を検索がバインドされたオブジェクトで許可されていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-121">Looks up a localized string similar to This operation is forbidden on bound objects..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationForbiddenOnUnboundObjects">
      <MemberSignature Language="C#" Value="public static string OperationForbiddenOnUnboundObjects { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string OperationForbiddenOnUnboundObjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.OperationForbiddenOnUnboundObjects" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property OperationForbiddenOnUnboundObjects As String" />
      <MemberSignature Language="F#" Value="member this.OperationForbiddenOnUnboundObjects : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.OperationForbiddenOnUnboundObjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-122">この操作に類似したローカライズされた文字列を検索がバインドされていないオブジェクトで許可されていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-122">Looks up a localized string similar to This operation is forbidden on unbound objects..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertiesReadAccessViolation">
      <MemberSignature Language="C#" Value="public static string PropertiesReadAccessViolation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string PropertiesReadAccessViolation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.PropertiesReadAccessViolation" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property PropertiesReadAccessViolation As String" />
      <MemberSignature Language="F#" Value="member this.PropertiesReadAccessViolation : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.PropertiesReadAccessViolation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-123">オブジェクトが {1} 状態中は、プロパティ {0} に類似したローカライズされた文字列の検索を読み取ることができません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-123">Looks up a localized string similar to The property {0} cannot be read while the object is in the {1} state..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertiesWriteAccessViolation">
      <MemberSignature Language="C#" Value="public static string PropertiesWriteAccessViolation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string PropertiesWriteAccessViolation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.PropertiesWriteAccessViolation" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property PropertiesWriteAccessViolation As String" />
      <MemberSignature Language="F#" Value="member this.PropertiesWriteAccessViolation : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.PropertiesWriteAccessViolation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-124">オブジェクトが {1} 状態ではプロパティ {0} に類似したローカライズされた文字列を検索できない変更する.</span><span class="sxs-lookup"><span data-stu-id="a85ec-124">Looks up a localized string similar to The property {0} cannot be modified while the object is in the {1} state..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceManager">
      <MemberSignature Language="C#" Value="public static System.Resources.ResourceManager ResourceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class System.Resources.ResourceManager ResourceManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.ResourceManager" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property ResourceManager As ResourceManager" />
      <MemberSignature Language="F#" Value="member this.ResourceManager : System.Resources.ResourceManager" Usage="Microsoft.Azure.Batch.BatchErrorMessages.ResourceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Advanced)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Resources.ResourceManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-125">このクラスによって使用される、キャッシュされた ResourceManager のインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="a85ec-125">Returns the cached ResourceManager instance used by this class.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRangeCannotHaveEndLessThanStart">
      <MemberSignature Language="C#" Value="public static string TaskIdRangeCannotHaveEndLessThanStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TaskIdRangeCannotHaveEndLessThanStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveEndLessThanStart" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TaskIdRangeCannotHaveEndLessThanStart As String" />
      <MemberSignature Language="F#" Value="member this.TaskIdRangeCannotHaveEndLessThanStart : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveEndLessThanStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-126">最後のタスクの id に類似したローカライズされた文字列を検索は、開始タスク id 以上にする必要があります..</span><span class="sxs-lookup"><span data-stu-id="a85ec-126">Looks up a localized string similar to End task id must be greater than or equal to the start task id..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRangeCannotHaveNegativeEnd">
      <MemberSignature Language="C#" Value="public static string TaskIdRangeCannotHaveNegativeEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TaskIdRangeCannotHaveNegativeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveNegativeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TaskIdRangeCannotHaveNegativeEnd As String" />
      <MemberSignature Language="F#" Value="member this.TaskIdRangeCannotHaveNegativeEnd : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveNegativeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-127">最後のタスクの id に類似したローカライズされた文字列を検索は、0 以上にする必要があります.</span><span class="sxs-lookup"><span data-stu-id="a85ec-127">Looks up a localized string similar to End task id must be greater or equal to 0..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRangeCannotHaveNegativeStart">
      <MemberSignature Language="C#" Value="public static string TaskIdRangeCannotHaveNegativeStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TaskIdRangeCannotHaveNegativeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveNegativeStart" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TaskIdRangeCannotHaveNegativeStart As String" />
      <MemberSignature Language="F#" Value="member this.TaskIdRangeCannotHaveNegativeStart : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TaskIdRangeCannotHaveNegativeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-128">最初のタスクの id に類似したローカライズされた文字列の検索は、0 以上にする必要があります.</span><span class="sxs-lookup"><span data-stu-id="a85ec-128">Looks up a localized string similar to First task id must be greater or equal to 0..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeDoesNotSupportExpandClause">
      <MemberSignature Language="C#" Value="public static string TypeDoesNotSupportExpandClause { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TypeDoesNotSupportExpandClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportExpandClause" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TypeDoesNotSupportExpandClause As String" />
      <MemberSignature Language="F#" Value="member this.TypeDoesNotSupportExpandClause : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportExpandClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-129">型 {0} に類似したローカライズされた文字列の検索は、[展開] 句をサポートしていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-129">Looks up a localized string similar to Type {0} does not support an expand clause..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeDoesNotSupportFilterClause">
      <MemberSignature Language="C#" Value="public static string TypeDoesNotSupportFilterClause { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TypeDoesNotSupportFilterClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportFilterClause" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TypeDoesNotSupportFilterClause As String" />
      <MemberSignature Language="F#" Value="member this.TypeDoesNotSupportFilterClause : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportFilterClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-130">{0} 型に類似したローカライズされた文字列の検索は、フィルター句をサポートしていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-130">Looks up a localized string similar to Type {0} does not support a filter clause..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeDoesNotSupportSelectClause">
      <MemberSignature Language="C#" Value="public static string TypeDoesNotSupportSelectClause { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TypeDoesNotSupportSelectClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportSelectClause" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TypeDoesNotSupportSelectClause As String" />
      <MemberSignature Language="F#" Value="member this.TypeDoesNotSupportSelectClause : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.TypeDoesNotSupportSelectClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-131">{0} 型に類似したローカライズされた文字列の検索は、select 句をサポートしていません.</span><span class="sxs-lookup"><span data-stu-id="a85ec-131">Looks up a localized string similar to Type {0} does not support a select clause..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownAddTaskResultAction">
      <MemberSignature Language="C#" Value="public static string UnknownAddTaskResultAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string UnknownAddTaskResultAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchErrorMessages.UnknownAddTaskResultAction" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property UnknownAddTaskResultAction As String" />
      <MemberSignature Language="F#" Value="member this.UnknownAddTaskResultAction : string" Usage="Microsoft.Azure.Batch.BatchErrorMessages.UnknownAddTaskResultAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
               <span data-ttu-id="a85ec-132">不明な AddTaskResultAction 値と同様にローカライズされた文字列を検索: {0}。</span><span class="sxs-lookup"><span data-stu-id="a85ec-132">Looks up a localized string similar to Unknown AddTaskResultAction value: {0}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>