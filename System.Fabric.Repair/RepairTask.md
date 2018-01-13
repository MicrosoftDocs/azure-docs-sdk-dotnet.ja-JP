<Type Name="RepairTask" FullName="System.Fabric.Repair.RepairTask">
  <TypeSignature Language="C#" Value="public class RepairTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RepairTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTask" />
  <TypeSignature Language="VB.NET" Value="Public Class RepairTask" />
  <TypeSignature Language="F#" Value="type RepairTask = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>修復の種類が要求された、その進行状況、およびその最終的な結果は何でしたに関する情報を含む修復タスクを表します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public string Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Action" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As String" />
      <MemberSignature Language="F#" Value="member this.Action : string" Usage="System.Fabric.Repair.RepairTask.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>要求された修復アクションを取得します。</para>
        </summary>
        <value>
          <para>要求された修復アクション。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApprovedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ApprovedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ApprovedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ApprovedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApprovedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ApprovedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ApprovedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが承認済みの状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが承認済みの状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClaimedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClaimedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ClaimedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClaimedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClaimedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ClaimedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが Claimed 状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが Claimed 状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CompletedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CompletedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.CompletedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CompletedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.CompletedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが完了済みの状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが完了済みの状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.CreatedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.CreatedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが作成済みの状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが Created 状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Repair.RepairTask.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または目的の説明または修復タスクの他の情報の詳細を設定します。</para>
        </summary>
        <value>
          <para>目的は、または修復タスクの他の情報の詳細の説明。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutingTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExecutingTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExecutingTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ExecutingTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutingTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExecutingTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.ExecutingTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが実行中の状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが実行中の状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Executor">
      <MemberSignature Language="C#" Value="public string Executor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Executor" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Executor" />
      <MemberSignature Language="VB.NET" Value="Public Property Executor As String" />
      <MemberSignature Language="F#" Value="member this.Executor : string with get, set" Usage="System.Fabric.Repair.RepairTask.Executor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復の実行子の名前を設定します。</para>
        </summary>
        <value>
          <para>修復の実行子の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutorData">
      <MemberSignature Language="C#" Value="public string ExecutorData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExecutorData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ExecutorData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutorData As String" />
      <MemberSignature Language="F#" Value="member this.ExecutorData : string with get, set" Usage="System.Fabric.Repair.RepairTask.ExecutorData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復の実行子は、内部状態の保存に使用できるデータ文字列を設定します。</para>
        </summary>
        <value>
          <para>修復の実行子は、内部状態の保存に使用できるデータ文字列です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskFlags Flags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskFlags Flags" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Flags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Flags As RepairTaskFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : System.Fabric.Repair.RepairTaskFlags" Usage="System.Fabric.Repair.RepairTask.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクの状態に関する追加情報を指定するフラグを取得します。</para>
        </summary>
        <value>
          <para>修復タスクの状態に関する追加情報を指定するフラグ。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Impact">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairImpactDescription Impact { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairImpactDescription Impact" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Impact" />
      <MemberSignature Language="VB.NET" Value="Public Property Impact As RepairImpactDescription" />
      <MemberSignature Language="F#" Value="member this.Impact : System.Fabric.Repair.RepairImpactDescription with get, set" Usage="System.Fabric.Repair.RepairTask.Impact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairImpactDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復の影響について説明するオブジェクトを取得します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.Fabric.Repair.RepairImpactDescription" />修復の影響について説明するオブジェクト。</para>
        </value>
        <remarks>
          <para>準備状態に遷移する時に修復 executor によって影響を指定してください。 影響オブジェクトでは、システムが修復の実行を承認する前に、修復の影響の準備を行うどのようなアクションを決定します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformPreparingHealthCheck">
      <MemberSignature Language="C#" Value="public bool PerformPreparingHealthCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PerformPreparingHealthCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PerformPreparingHealthCheck" />
      <MemberSignature Language="VB.NET" Value="Public Property PerformPreparingHealthCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.PerformPreparingHealthCheck : bool with get, set" Usage="System.Fabric.Repair.RepairTask.PerformPreparingHealthCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または正常性チェックの修復タスクが準備状態になったときに実行する必要がかどうかを決定する値を設定します。</para>
        </summary>
        <value>
          <para>正常性チェックの修復タスクが準備状態になったときに実行する必要がかどうかを決定する値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformRestoringHealthCheck">
      <MemberSignature Language="C#" Value="public bool PerformRestoringHealthCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PerformRestoringHealthCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PerformRestoringHealthCheck" />
      <MemberSignature Language="VB.NET" Value="Public Property PerformRestoringHealthCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.PerformRestoringHealthCheck : bool with get, set" Usage="System.Fabric.Repair.RepairTask.PerformRestoringHealthCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または正常性チェックの修復タスクが Restoring 状態になったときに実行する必要がかどうかを決定する値を設定します。</para>
        </summary>
        <value>
          <para>正常性チェックの修復タスクが Restoring 状態になったときに実行する必要がかどうかを決定する値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckEndTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingHealthCheckEndTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingHealthCheckEndTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckEndTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckEndTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckEndTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckEndTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが正常性を完了した時刻を取得、準備状態で確認してください。</para>
        </summary>
        <value>
          <para>修復タスクが正常性を完了すると時間は、準備状態で確認します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckStartTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingHealthCheckStartTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingHealthCheckStartTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckStartTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckStartTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckStartTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckStartTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、正常に開始されたときに時刻を取得、準備状態で確認してください。</para>
        </summary>
        <value>
          <para>修復タスクが、正常に開始されたときに時間は、準備状態で確認します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingHealthCheckState">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskHealthCheckState PreparingHealthCheckState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskHealthCheckState PreparingHealthCheckState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingHealthCheckState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingHealthCheckState As RepairTaskHealthCheckState" />
      <MemberSignature Language="F#" Value="member this.PreparingHealthCheckState : System.Fabric.Repair.RepairTaskHealthCheckState" Usage="System.Fabric.Repair.RepairTask.PreparingHealthCheckState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、準備状態のときは、正常性チェックのワークフローの状態を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが、準備状態のときの正常性チェックのワークフローの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreparingTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreparingTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreparingTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.PreparingTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreparingTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreparingTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.PreparingTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、準備状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが、準備状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckEndTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringHealthCheckEndTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringHealthCheckEndTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckEndTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckEndTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckEndTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckEndTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが正常性を完了した時刻を取得、Restoring 状態で確認してください。</para>
        </summary>
        <value>
          <para>修復タスクが正常性を完了した時刻は Restoring 状態で確認してください。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckStartTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringHealthCheckStartTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringHealthCheckStartTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckStartTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckStartTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckStartTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckStartTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、正常に開始されたときに時刻を取得、Restoring 状態で確認してください。</para>
        </summary>
        <value>
          <para>修復タスク状態の開始時刻は Restoring 状態で確認してください。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringHealthCheckState">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskHealthCheckState RestoringHealthCheckState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskHealthCheckState RestoringHealthCheckState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringHealthCheckState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringHealthCheckState As RepairTaskHealthCheckState" />
      <MemberSignature Language="F#" Value="member this.RestoringHealthCheckState : System.Fabric.Repair.RepairTaskHealthCheckState" Usage="System.Fabric.Repair.RepairTask.RestoringHealthCheckState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、Restoring 状態のときは、正常性チェックのワークフローの状態を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが、Restoring 状態のときの正常性チェックのワークフローの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoringTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestoringTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestoringTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.RestoringTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestoringTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestoringTimestamp : Nullable&lt;DateTime&gt;" Usage="System.Fabric.Repair.RepairTask.RestoringTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクが、Restoring 状態を入力した時間を取得します。</para>
        </summary>
        <value>
          <para>修復タスクが、Restoring 状態を入力した時刻。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCode">
      <MemberSignature Language="C#" Value="public int ResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ResultCode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ResultCode : int with get, set" Usage="System.Fabric.Repair.RepairTask.ResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復のタスクの実行の結果に関する詳細を提供する値を設定します。</para>
        </summary>
        <value>
          <para>修復タスクの実行の結果に関する詳細を提供する値。</para>
        </value>
        <remarks>
          <para>この値は、HRESULT を指定する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultDetails">
      <MemberSignature Language="C#" Value="public string ResultDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResultDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultDetails As String" />
      <MemberSignature Language="F#" Value="member this.ResultDetails : string with get, set" Usage="System.Fabric.Repair.RepairTask.ResultDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復のタスクの実行の結果に関する追加情報を指定する文字列を設定します。</para>
        </summary>
        <value>
          <para>修復タスクの実行の結果に関する追加情報を指定する文字列。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskResult ResultStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskResult ResultStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.ResultStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultStatus As RepairTaskResult" />
      <MemberSignature Language="F#" Value="member this.ResultStatus : System.Fabric.Repair.RepairTaskResult with get, set" Usage="System.Fabric.Repair.RepairTask.ResultStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復のタスクの実行の全体的な結果を示す値を設定します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.Fabric.Repair.RepairTaskResult" />修復タスクの実行の全体的な結果を示す値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairScopeIdentifier Scope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairScopeIdentifier Scope" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Scope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scope As RepairScopeIdentifier" />
      <MemberSignature Language="F#" Value="member this.Scope : System.Fabric.Repair.RepairScopeIdentifier" Usage="System.Fabric.Repair.RepairTask.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairScopeIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクのスコープを表すオブジェクトを取得します。</para>
        </summary>
        <value>
          <para>A<see cref="T:System.Fabric.Repair.RepairScopeIdentifier" />修復作業のスコープを記述するオブジェクト。</para>
        </value>
        <remarks>
          <para>修復作業のスコープでは、どのアクセスに対してチェックが実行修復タスクが作成、変更、削除、または取得時にリソースを決定します。  修復タスクのスコープ内で修復によって影響を受けるエンティティが含まれている必要があります。  たとえば、ノードに影響を与える修復では、クラスターのスコープの下で修復タスクを作成することが必要です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.RepairTaskState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As RepairTaskState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.Repair.RepairTaskState with get, set" Usage="System.Fabric.Repair.RepairTask.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復タスクのワークフローの状態を設定します。</para>
        </summary>
        <value>
          <para>修復タスクのワークフローの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTargetDescription Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairTargetDescription Target" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As RepairTargetDescription" />
      <MemberSignature Language="F#" Value="member this.Target : System.Fabric.Repair.RepairTargetDescription with get, set" Usage="System.Fabric.Repair.RepairTask.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTargetDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または要求された修復アクションのターゲット エンティティを表すオブジェクトを設定します。</para>
        </summary>
        <value>
          <para>要求された修復アクションが対象とするエンティティを表すオブジェクトです。</para>
        </value>
        <remarks>
          <para>ターゲットは、修復アクションに特定のターゲットに関する情報が必要としない場合は null にする可能性があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string" Usage="System.Fabric.Repair.RepairTask.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>修復タスクの識別子を取得します。</para>
        </summary>
        <value>
          <para>修復タスクの識別子。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public long Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Version" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTask.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Long" />
      <MemberSignature Language="F#" Value="member this.Version : int64 with get, set" Usage="System.Fabric.Repair.RepairTask.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または修復タスクのバージョンを設定します。</para>
        </summary>
        <value>
          <para>修復タスクのバージョン。</para>
        </value>
        <remarks>
          <para>新しい修復タスクを作成するときに、バージョンが 0 に設定する必要があります。  UpdateRepairExecutionStateAsync メソッドを使用して修復作業を更新するには、オプティミスティック同時実行チェックのバージョンが使用されます。  バージョンが 0 に設定されている場合、更新プログラムは書き込みの競合の確認されません。  場合は、バージョンに設定されている 0 以外の値では、更新プログラムは、修復作業の実際の現在のバージョンがこの値に一致する場合にのみ成功します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>