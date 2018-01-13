<Type Name="NodeRemoveParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter">
  <TypeSignature Language="C#" Value="public class NodeRemoveParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeRemoveParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeRemoveParameter" />
  <TypeSignature Language="F#" Value="type NodeRemoveParameter = class" />
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
            削除するためのオプションは、プールからノードを計算します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRemoveParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.#ctor" />
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
            NodeRemoveParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRemoveParameter (System.Collections.Generic.IList&lt;string&gt; nodeList, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; nodeList, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.#ctor(System.Collections.Generic.IList{System.String},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeList As IList(Of String), Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter : System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter (nodeList, resizeTimeout, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeList">指定したプールから削除するコンピューティング ノードの Id を含む一覧です。</param>
        <param name="resizeTimeout">プールにコンピューティング ノードの削除のタイムアウト。</param>
        <param name="nodeDeallocationOption">割り当て解除用に選択されている後のノードとその実行中のタスクの操作を決定します。</param>
        <summary>
            NodeRemoveParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の割り当て解除用に選択されている後のノードとその実行中のタスクの操作を決定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は requeue です。 使用可能な値が含まれます: 'requeue'、'終了'、'taskCompletion'、'retainedData'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NodeList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NodeList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeList" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NodeList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.NodeList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定したプールから削除するコンピューティング ノードの Id を含むリストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resizeTimeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールにコンピューティング ノードの削除のためのタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、15 分です。 最小値は、5 分です。 5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeRemoveParameter.Validate " />
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