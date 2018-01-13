<Type Name="TaskUpdateParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter">
  <TypeSignature Language="C#" Value="public class TaskUpdateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskUpdateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskUpdateParameter" />
  <TypeSignature Language="F#" Value="type TaskUpdateParameter = class" />
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
            一連のタスクに変更します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskUpdateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.#ctor" />
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
            TaskUpdateParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskUpdateParameter (Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.TaskConstraints)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional constraints As TaskConstraints = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter constraints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
      </Parameters>
      <Docs>
        <param name="constraints">このタスクに適用される制約します。</param>
        <summary>
            TaskUpdateParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このタスクに適用される制約を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、タスクは、既定の制約を付与します。 複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>