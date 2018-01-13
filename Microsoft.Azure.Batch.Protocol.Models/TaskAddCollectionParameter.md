<Type Name="TaskAddCollectionParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter">
  <TypeSignature Language="C#" Value="public class TaskAddCollectionParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddCollectionParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddCollectionParameter" />
  <TypeSignature Language="F#" Value="type TaskAddCollectionParameter = class" />
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
            タスクを追加して Azure Batch のコレクション。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddCollectionParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter.#ctor" />
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
            TaskAddCollectionParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddCollectionParameter (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As IList(Of TaskAddParameter))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="value">追加するタスクのコレクション。</param>
        <summary>
            TaskAddCollectionParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddCollectionParameter.Validate " />
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of TaskAddParameter)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionParameter.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加するタスクのコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。
            (たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>