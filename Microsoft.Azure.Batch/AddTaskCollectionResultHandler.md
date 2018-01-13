<Type Name="AddTaskCollectionResultHandler" FullName="Microsoft.Azure.Batch.AddTaskCollectionResultHandler">
  <TypeSignature Language="C#" Value="public class AddTaskCollectionResultHandler : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddTaskCollectionResultHandler extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class AddTaskCollectionResultHandler&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type AddTaskCollectionResultHandler = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            A<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />ジョブに複数のタスクが再試行を追加するための操作をどのような条件下で指定に使用できるを終了する/成功すると見なされます。
            </summary>
    <remarks>この動作を明示的に指定する必要はありません。そうしないと、既定の動作が使用されます。  この動作を使用して、<see cref="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler(Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken)" />条件。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddTaskCollectionResultHandler (Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt; resultHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`3&lt;class Microsoft.Azure.Batch.AddTaskResult, valuetype System.Threading.CancellationToken, valuetype Microsoft.Azure.Batch.AddTaskResultStatus&gt; resultHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.#ctor(System.Func{Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resultHandler As Func(Of AddTaskResult, CancellationToken, AddTaskResultStatus))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.AddTaskCollectionResultHandler : Func&lt;Microsoft.Azure.Batch.AddTaskResult, System.Threading.CancellationToken, Microsoft.Azure.Batch.AddTaskResultStatus&gt; -&gt; Microsoft.Azure.Batch.AddTaskCollectionResultHandler" Usage="new Microsoft.Azure.Batch.AddTaskCollectionResultHandler resultHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resultHandler" Type="System.Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="resultHandler">かどうか、特定のタスクの追加操作は成功したか失敗したと見なされます、再試行するかどうかを定義する関数。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />指定された結果ハンドラー関数を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAddTaskCollectionResultHandler">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.AddTaskResultStatus DefaultAddTaskCollectionResultHandler (Microsoft.Azure.Batch.AddTaskResult addTaskResult, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.Batch.AddTaskResultStatus DefaultAddTaskCollectionResultHandler(class Microsoft.Azure.Batch.AddTaskResult addTaskResult, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler(Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DefaultAddTaskCollectionResultHandler : Microsoft.Azure.Batch.AddTaskResult * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.AddTaskResultStatus" Usage="Microsoft.Azure.Batch.AddTaskCollectionResultHandler.DefaultAddTaskCollectionResultHandler (addTaskResult, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addTaskResult" Type="Microsoft.Azure.Batch.AddTaskResult" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="addTaskResult">1 つのタスクの追加操作の結果。</param>
        <param name="cancellationToken">AddTaskCollection 操作に関連付けられたキャンセル トークン。</param>
        <summary>
            既定の結果ハンドラー、<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。 このハンドラーは、成功および 'TaskExists' エラー成功として処理、サーバー エラー (HTTP 5xx) を再試行しがスローされます<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" />クライアント エラー (HTTP 4 xx) にします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.AddTaskResultStatus" />を示すかどうか、<paramref name="addTaskResult" />成功、または再試行を要求として分類されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt; ResultHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.Azure.Batch.AddTaskResult, valuetype System.Threading.CancellationToken, valuetype Microsoft.Azure.Batch.AddTaskResultStatus&gt; ResultHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AddTaskCollectionResultHandler.ResultHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultHandler As Func(Of AddTaskResult, CancellationToken, AddTaskResultStatus)" />
      <MemberSignature Language="F#" Value="member this.ResultHandler : Func&lt;Microsoft.Azure.Batch.AddTaskResult, System.Threading.CancellationToken, Microsoft.Azure.Batch.AddTaskResultStatus&gt; with get, set" Usage="Microsoft.Azure.Batch.AddTaskCollectionResultHandler.ResultHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.Batch.AddTaskResult,System.Threading.CancellationToken,Microsoft.Azure.Batch.AddTaskResultStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するかどうか、特定のタスクの追加操作は成功したか失敗したと見なされます、再試行するかどうかを定義する関数。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>