<Type Name="TaskOutputKind" FullName="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind">
  <TypeSignature Language="C#" Value="public sealed class TaskOutputKind : IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TaskOutputKind extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TaskOutputKind&#xA;Implements IEquatable(Of TaskOutputKind)" />
  <TypeSignature Language="F#" Value="type TaskOutputKind = class&#xA;    interface IEquatable&lt;TaskOutputKind&gt;&#xA;    interface IOutputKind" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f9491-101">メイン タスクの出力、またはタスクの出力のプレビューなど、ジョブの出力のカテゴリまたはタスクの処理のログを表します。</span><span class="sxs-lookup"><span data-stu-id="f9491-101">Represents a category of job outputs, such as the main task output, or a preview of the task output, or a log of the task processing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Custom">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind Custom (string text);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind Custom(string text) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.Custom(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Custom (text As String) As TaskOutputKind" />
      <MemberSignature Language="F#" Value="static member Custom : string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.Custom text" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="text"><span data-ttu-id="f9491-102">カスタム TaskOutputKind のテキストの識別子です。</span><span class="sxs-lookup"><span data-stu-id="f9491-102">A text identifier for the custom TaskOutputKind.</span></span></param>
        <summary>
            <span data-ttu-id="f9491-103">取得、<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />タスクの出力のカスタム カテゴリを表すです。</span><span class="sxs-lookup"><span data-stu-id="f9491-103">Gets a <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing a custom category of task outputs.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-104">指定されたテキストで TaskOutputKind です。</span><span class="sxs-lookup"><span data-stu-id="f9491-104">A TaskOutputKind with the specified text.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="f9491-105"><paramref name="text" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="f9491-105"><paramref name="text" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="f9491-106"><paramref name="text" /> が空です。</span><span class="sxs-lookup"><span data-stu-id="f9491-106"><paramref name="text" /> is empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.Equals(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As TaskOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; bool" Usage="taskOutputKind.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="f9491-107">このインスタンスと比較する TaskOutputKind です。</span><span class="sxs-lookup"><span data-stu-id="f9491-107">The TaskOutputKind to compare to this instance.</span></span></param>
        <summary>
            <span data-ttu-id="f9491-108">このインスタンスと別に指定されているかどうかを determinates<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />値が同じであります。</span><span class="sxs-lookup"><span data-stu-id="f9491-108">Determinates whether this instance and another specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> have the same value.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-109">true の場合の値、<paramref name="other" />パラメーターは、このインスタンスの値と同じです。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="f9491-109">true if the value of the <paramref name="other" /> parameter is the same as the value of this instance; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="taskOutputKind.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="f9491-110">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9491-110">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="f9491-111">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="f9491-111">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-112">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f9491-112">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="taskOutputKind.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9491-113">この <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> のハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="f9491-113">Returns the hash code for this <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-114">32 ビット符号付き整数ハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="f9491-114">A 32-bit signed integer hash code.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind x, Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.op_Equality(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (x As TaskOutputKind, y As TaskOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; bool" Usage="x = y" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="f9491-115">比較する最初の TaskOutputKind します。</span><span class="sxs-lookup"><span data-stu-id="f9491-115">The first TaskOutputKind to compare.</span></span></param>
        <param name="y"><span data-ttu-id="f9491-116">比較する 2 番目の TaskOutputKind します。</span><span class="sxs-lookup"><span data-stu-id="f9491-116">The second TaskOutputKind to compare.</span></span></param>
        <summary>
            <span data-ttu-id="f9491-117">指定した 2 つあるかどうかを判断<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />インスタンスが同じ値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9491-117">Determines whether two specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> instances have the same value.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-118">true の場合の値<paramref name="x" />はの値と同じ<paramref name="y" />。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="f9491-118">true if the value of <paramref name="x" /> is the same as the value of <paramref name="y" />; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind x, Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind y);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind x, class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind y) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.op_Inequality(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (x As TaskOutputKind, y As TaskOutputKind) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; bool" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.op_Inequality (x, y)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="x" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="y" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="x"><span data-ttu-id="f9491-119">比較する最初の TaskOutputKind します。</span><span class="sxs-lookup"><span data-stu-id="f9491-119">The first TaskOutputKind to compare.</span></span></param>
        <param name="y"><span data-ttu-id="f9491-120">比較する 2 番目の TaskOutputKind します。</span><span class="sxs-lookup"><span data-stu-id="f9491-120">The second TaskOutputKind to compare.</span></span></param>
        <summary>
            <span data-ttu-id="f9491-121">指定した 2 つあるかどうかを判断<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />インスタンスが異なる値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f9491-121">Determines whether two specified <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> instances have different values.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-122">true の場合の値<paramref name="x" />の値とは異なる<paramref name="y" />。 それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="f9491-122">true if the value of <paramref name="x" /> is different from the value of <paramref name="y" />; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIntermediate">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskIntermediate;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskIntermediate" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskIntermediate" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TaskIntermediate As TaskOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable TaskIntermediate : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskIntermediate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9491-123">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />診断またはチェックポイント処理のために永続化など、中間ファイルを表すです。</span><span class="sxs-lookup"><span data-stu-id="f9491-123">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing an intermediate file, for example being persisted for diagnostic or checkpointing purposes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskLog">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskLog;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskLog" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TaskLog As TaskOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable TaskLog : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9491-124">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />タスク処理のログを表すです。</span><span class="sxs-lookup"><span data-stu-id="f9491-124">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing a log of the task processing.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskOutput">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskOutput;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskOutput" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TaskOutput As TaskOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable TaskOutput : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9491-125">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />タスクの主要な出力を表すです。</span><span class="sxs-lookup"><span data-stu-id="f9491-125">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing the main output of a task.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskPreview">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskPreview;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind TaskPreview" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskPreview" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TaskPreview As TaskOutputKind " />
      <MemberSignature Language="F#" Value=" staticval mutable TaskPreview : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" Usage="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskPreview" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9491-126">A<see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />タスク出力のプレビューを表すです。</span><span class="sxs-lookup"><span data-stu-id="f9491-126">A <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> representing a preview of the task output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="taskOutputKind.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f9491-127">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="f9491-127">Returns a string that represents the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="f9491-128"><see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> のテキスト表現。</span><span class="sxs-lookup"><span data-stu-id="f9491-128">A textual representation of the <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>