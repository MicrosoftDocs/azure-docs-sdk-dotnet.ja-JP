<Type Name="JobConstraints" FullName="Microsoft.Azure.Batch.JobConstraints">
  <TypeSignature Language="C#" Value="public class JobConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobConstraints" />
  <TypeSignature Language="F#" Value="type JobConstraints = class&#xA;    interface ITransportObjectProvider&lt;JobConstraints&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="acdc0-101">ジョブの実行の制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="acdc0-101">Specifies the execution constraints for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.JobConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.JobConstraints" Usage="new Microsoft.Azure.Batch.JobConstraints (maxWallClockTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="acdc0-102">ジョブの実行は、最大の経過時間は、ジョブが作成された時点から計測されます。</span><span class="sxs-lookup"><span data-stu-id="acdc0-102">The maximum elapsed time that the job may run, measured from the time the job is created.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="acdc0-103">各タスクが再試行される最大回数。</span><span class="sxs-lookup"><span data-stu-id="acdc0-103">The maximum number of times each task may be retried.</span></span></param>
        <summary>
            <span data-ttu-id="acdc0-104"><see cref="T:Microsoft.Azure.Batch.JobConstraints" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="acdc0-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.JobConstraints" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.JobConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acdc0-105">取得または、各タスクが再試行される最大回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="acdc0-105">Gets or sets the maximum number of times each task may be retried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.JobConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="acdc0-106">取得またはジョブが作成された時点から計測されます、ジョブに実行できる最大経過時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="acdc0-106">Gets or sets the maximum elapsed time that the job may run, measured from the time the job is created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>