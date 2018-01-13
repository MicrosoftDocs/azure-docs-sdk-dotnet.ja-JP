<Type Name="TaskSchedulingPolicy" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy">
  <TypeSignature Language="C#" Value="public class TaskSchedulingPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskSchedulingPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskSchedulingPolicy" />
  <TypeSignature Language="F#" Value="type TaskSchedulingPolicy = class" />
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
            コンピューティング ノード間での作業の分散方法を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskSchedulingPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy.#ctor" />
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
            TaskSchedulingPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskSchedulingPolicy (Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType nodeFillType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType nodeFillType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy.#ctor(Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeFillType As ComputeNodeFillType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy nodeFillType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeFillType" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType" />
      </Parameters>
      <Docs>
        <param name="nodeFillType">どのタスクはプール内のコンピューティング ノード間で分散されます。</param>
        <summary>
            TaskSchedulingPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeFillType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType NodeFillType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType NodeFillType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy.NodeFillType" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeFillType As ComputeNodeFillType" />
      <MemberSignature Language="F#" Value="member this.NodeFillType : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy.NodeFillType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeFillType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: '分散'、'pack'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskSchedulingPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskSchedulingPolicy.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>