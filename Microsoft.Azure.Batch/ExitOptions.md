<Type Name="ExitOptions" FullName="Microsoft.Azure.Batch.ExitOptions">
  <TypeSignature Language="C#" Value="public class ExitOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitOptions" />
  <TypeSignature Language="F#" Value="type ExitOptions = class&#xA;    interface ITransportObjectProvider&lt;ExitOptions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="426cb-101">方法バッチ サービスは、特定の終了条件に応答する必要があります。</span><span class="sxs-lookup"><span data-stu-id="426cb-101">How the Batch service should respond to a particular exit condition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="426cb-102"><see cref="T:Microsoft.Azure.Batch.ExitOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="426cb-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ExitOptions" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt; DependencyAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DependencyAction&gt; DependencyAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitOptions.DependencyAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyAction As Nullable(Of DependencyAction)" />
      <MemberSignature Language="F#" Value="member this.DependencyAction : Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitOptions.DependencyAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="426cb-103">取得または、このタスクに依存しているタスクに対して、バッチ サービスが実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="426cb-103">Gets or sets an action that the Batch service should take on tasks that depend on this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="426cb-104">既定値は<see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Satisfy" />の終了コード 0、および<see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Block" />の他のすべてを終了する条件。</span><span class="sxs-lookup"><span data-stu-id="426cb-104">The default is <see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Satisfy" /> for exit code 0, and <see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Block" /> for all other exit conditions.</span></span> <span data-ttu-id="426cb-105">場合、ジョブの<see cref="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />が false の場合、このプロパティ セットを持つタスクを追加することはできません。</span><span class="sxs-lookup"><span data-stu-id="426cb-105">If the job's <see cref="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" /> is false, you cannot add a task with this property set.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt; JobAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobAction&gt; JobAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitOptions.JobAction" />
      <MemberSignature Language="VB.NET" Value="Public Property JobAction As Nullable(Of JobAction)" />
      <MemberSignature Language="F#" Value="member this.JobAction : Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitOptions.JobAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="426cb-106">指定された終了条件と、ジョブのタスクが完了した場合、タスクを含むジョブを実行するアクションを取得または<see cref="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />プロパティは<see cref="F:Microsoft.Azure.Batch.Common.OnTaskFailure.PerformExitOptionsJobAction" />します。</span><span class="sxs-lookup"><span data-stu-id="426cb-106">Gets or sets an action to take on the job containing the task, if the task completes with the given exit condition and the job's <see cref="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" /> property is <see cref="F:Microsoft.Azure.Batch.Common.OnTaskFailure.PerformExitOptionsJobAction" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>