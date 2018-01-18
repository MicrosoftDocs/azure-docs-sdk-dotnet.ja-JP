<Type Name="TaskIdRange" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange">
  <TypeSignature Language="C#" Value="public class TaskIdRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskIdRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskIdRange" />
  <TypeSignature Language="F#" Value="type TaskIdRange = class" />
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
            <span data-ttu-id="f2043-101">タスク、タスクに依存できる Id の範囲。</span><span class="sxs-lookup"><span data-stu-id="f2043-101">A range of task IDs that a task can depend on.</span></span> <span data-ttu-id="f2043-102">依存タスクをスケジュールする前に、範囲の Id を持つすべてのタスクが正常に完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2043-102">All tasks with IDs in the range must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f2043-103">開始と範囲の終了は、包括的です。</span><span class="sxs-lookup"><span data-stu-id="f2043-103">The start and end of the range are inclusive.</span></span> <span data-ttu-id="f2043-104">たとえば、範囲は起動 9 と 12 の終了タスク '9'、' 10'、'11' と ' 12' を表します。</span><span class="sxs-lookup"><span data-stu-id="f2043-104">For example, if a range has start 9 and end 12, then it represents tasks '9', '10', '11' and '12'.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.#ctor" />
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
            <span data-ttu-id="f2043-105">TaskIdRange クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f2043-105">Initializes a new instance of the TaskIdRange class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Integer, end As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskIdRange : int * int -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskIdRange" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskIdRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="f2043-106">範囲の最初のタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f2043-106">The first task ID in the range.</span></span></param>
        <param name="end"><span data-ttu-id="f2043-107">範囲の最後のタスクの ID。</span><span class="sxs-lookup"><span data-stu-id="f2043-107">The last task ID in the range.</span></span></param>
        <summary>
            <span data-ttu-id="f2043-108">TaskIdRange クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f2043-108">Initializes a new instance of the TaskIdRange class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.End" />
      <MemberSignature Language="VB.NET" Value="Public Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2043-109">取得または範囲の最後のタスクの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="f2043-109">Gets or sets the last task ID in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2043-110">取得または範囲の最初のタスクの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="f2043-110">Gets or sets the first task ID in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskIdRange.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskIdRange.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2043-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f2043-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f2043-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f2043-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>