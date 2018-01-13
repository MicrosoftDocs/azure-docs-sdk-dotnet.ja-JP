<Type Name="JobBasePropertiesConstraints" FullName="Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints">
  <TypeSignature Language="C#" Value="public class JobBasePropertiesConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobBasePropertiesConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class JobBasePropertiesConstraints" />
  <TypeSignature Language="F#" Value="type JobBasePropertiesConstraints = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c2bf6-101">ジョブに関連付けられている制約。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-101">Constraints associated with the Job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobBasePropertiesConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2bf6-102">JobBasePropertiesConstraints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-102">Initializes a new instance of the JobBasePropertiesConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobBasePropertiesConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints.#ctor(System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints : Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints maxWallClockTime" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="c2bf6-103">ジョブを実行できる最大時間。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-103">Max time the job can run.</span></span></param>
        <summary>
            <span data-ttu-id="c2bf6-104">JobBasePropertiesConstraints クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-104">Initializes a new instance of the JobBasePropertiesConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2bf6-105">取得またはジョブを実行できる最大時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-105">Gets or sets max time the job can run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c2bf6-106">既定値 = 1 週間です。</span><span class="sxs-lookup"><span data-stu-id="c2bf6-106">Default Value = 1 week.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>