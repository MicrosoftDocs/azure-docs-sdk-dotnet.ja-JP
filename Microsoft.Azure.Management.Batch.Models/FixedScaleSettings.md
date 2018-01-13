<Type Name="FixedScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings">
  <TypeSignature Language="C#" Value="public class FixedScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FixedScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FixedScaleSettings" />
  <TypeSignature Language="F#" Value="type FixedScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プールのスケール設定を固定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FixedScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FixedScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FixedScaleSettings (Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional targetDedicatedNodes As Nullable(Of Integer) = null, Optional targetLowPriorityNodes As Nullable(Of Integer) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.FixedScaleSettings : Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; -&gt; Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.FixedScaleSettings (resizeTimeout, targetDedicatedNodes, targetLowPriorityNodes, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="resizeTimeout">プールにコンピューティング ノードの割り当てのタイムアウト。</param>
        <param name="targetDedicatedNodes">専用の目的の数は、プール内のノードを計算します。</param>
        <param name="targetLowPriorityNodes">目的の優先度の低い数は、プール内のノードを計算します。</param>
        <param name="nodeDeallocationOption">プールのサイズが減少している場合のノードとその実行中のタスクで処理を決定します。</param>
        <summary>
            FixedScaleSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、プールのサイズが減少している場合のノードとその実行中のタスクで処理を決定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、既定値はキューにします。 使用可能な値が含まれます: 'キューに再登録'、'終了'、'TaskCompletion'、'RetainedData'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            取得またはプールに割り当てるコンピューティング ノードの場合のタイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、15 分です。 最小値は、5 分です。 5 分より小さい値を指定する場合、バッチ サービスがエラー; で要求を拒否します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの目的専用のコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            少なくとも 1 つの targetDedicatedNodes、targetLowPriority ノードを設定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings.TargetLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールに目的の優先度の低いコンピューティング ノードの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            少なくとも 1 つの targetDedicatedNodes、targetLowPriority ノードを設定する必要があります。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>