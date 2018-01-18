<Type Name="ExitOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitOptions">
  <TypeSignature Language="C#" Value="public class ExitOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitOptions" />
  <TypeSignature Language="F#" Value="type ExitOptions = class" />
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
            <span data-ttu-id="007b1-101">バッチ サービスが特定の終了条件に応答する方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="007b1-101">Specifies how the Batch service responds to a particular exit condition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor" />
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
            <span data-ttu-id="007b1-102">ExitOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="007b1-102">Initializes a new instance of the ExitOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobAction},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DependencyAction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobAction As Nullable(Of JobAction) = null, Optional dependencyAction As Nullable(Of DependencyAction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions (jobAction, dependencyAction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;" />
        <Parameter Name="dependencyAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;" />
      </Parameters>
      <Docs>
        <param name="jobAction"><span data-ttu-id="007b1-103">指定された終了条件と、ジョブの onTaskFailed プロパティで、タスクが完了した場合、タスクを含む、ジョブで実行するアクションは、'performExitOptionsJobAction' です。</span><span class="sxs-lookup"><span data-stu-id="007b1-103">An action to take on the job containing the task, if the task completes with the given exit condition and the job's onTaskFailed property is 'performExitOptionsJobAction'.</span></span></param>
        <param name="dependencyAction"><span data-ttu-id="007b1-104">バッチ サービスがこのタスクに依存しているタスクを実行するアクション。</span><span class="sxs-lookup"><span data-stu-id="007b1-104">An action that the Batch service performs on tasks that depend on this task.</span></span></param>
        <summary>
            <span data-ttu-id="007b1-105">ExitOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="007b1-105">Initializes a new instance of the ExitOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyAction As Nullable(Of DependencyAction)" />
      <MemberSignature Language="F#" Value="member this.DependencyAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencyAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="007b1-106">取得またはバッチ サービスがこのタスクに依存しているタスクを実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="007b1-106">Gets or sets an action that the Batch service performs on tasks that depend on this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="007b1-107">既定では終了コード 0、およびその他のすべての終了条件には、' block' の '満たす' です。</span><span class="sxs-lookup"><span data-stu-id="007b1-107">The default is 'satisfy' for exit code 0, and 'block' for all other exit conditions.</span></span> <span data-ttu-id="007b1-108">DependencyAction プロパティを指定して、false がエラーを返します。 ジョブの usesTaskDependencies プロパティに設定されている場合と、追加のタスクの要求はエラーで失敗無効なプロパティ値です。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="007b1-108">If the job's usesTaskDependencies property is set to false, then specifying the dependencyAction property returns an error and the add task request fails with an invalid property value error; if you are calling the REST API directly, the HTTP status code is 400  (Bad Request).</span></span> <span data-ttu-id="007b1-109">使用可能な値が含まれます: 'を満たす'、'を ' ブロック</span><span class="sxs-lookup"><span data-stu-id="007b1-109">Possible values include: 'satisfy', 'block'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberSignature Language="VB.NET" Value="Public Property JobAction As Nullable(Of JobAction)" />
      <MemberSignature Language="F#" Value="member this.JobAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="007b1-110">取得または指定された終了条件を満たすタスクが完了したプロパティは、ジョブの onTaskFailed 'performExitOptionsJobAction' 場合に、タスクを含むジョブを実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="007b1-110">Gets or sets an action to take on the job containing the task, if the task completes with the given exit condition and the job's onTaskFailed property is 'performExitOptionsJobAction'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="007b1-111">既定値は none 終了コード 0 を他のすべての終了条件を終了します。</span><span class="sxs-lookup"><span data-stu-id="007b1-111">The default is none for exit code 0 and terminate for all other exit conditions.</span></span> <span data-ttu-id="007b1-112">ジョブの onTaskFailed プロパティが noAction の場合は、エラーを返します、このプロパティを指定して、追加のタスクの要求はエラーで失敗無効なプロパティ値です。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。</span><span class="sxs-lookup"><span data-stu-id="007b1-112">If the job's onTaskFailed property is noAction, then specifying this property returns an error and the add task request fails with an invalid property value error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span> <span data-ttu-id="007b1-113">使用可能な値が含まれます 'none'、'disable'、'終了'。</span><span class="sxs-lookup"><span data-stu-id="007b1-113">Possible values include: 'none', 'disable', 'terminate'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>