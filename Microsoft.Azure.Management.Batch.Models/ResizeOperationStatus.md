<Type Name="ResizeOperationStatus" FullName="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus">
  <TypeSignature Language="C#" Value="public class ResizeOperationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResizeOperationStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class ResizeOperationStatus" />
  <TypeSignature Language="F#" Value="type ResizeOperationStatus = class" />
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
            現在または最近完了したサイズ変更操作の詳細。
            </summary>
    <remarks>
            (AllocationState が安定である場合)、(プール AllocationState がサイズ変更) する場合は、現在の操作または前に完了した操作のいずれかを説明します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResizeOperationStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ResizeOperationStatus クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResizeOperationStatus (Nullable&lt;int&gt; targetDedicatedNodes = null, Nullable&lt;int&gt; targetLowPriorityNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption = null, Nullable&lt;DateTime&gt; startTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; errors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; targetDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; nodeDeallocationOption, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResizeError&gt; errors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption},System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ResizeError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional targetDedicatedNodes As Nullable(Of Integer) = null, Optional targetLowPriorityNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional nodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional startTime As Nullable(Of DateTime) = null, Optional errors As IList(Of ResizeError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; -&gt; Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" Usage="new Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus (targetDedicatedNodes, targetLowPriorityNodes, resizeTimeout, nodeDeallocationOption, startTime, errors)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt;" />
      </Parameters>
      <Docs>
        <param name="targetDedicatedNodes">専用の目的の数は、プール内のノードを計算します。</param>
        <param name="targetLowPriorityNodes">目的の優先度の低い数は、プール内のノードを計算します。</param>
        <param name="resizeTimeout">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。</param>
        <param name="nodeDeallocationOption">プールのサイズが減少している場合のノードとその実行中のタスクで処理を決定します。</param>
        <param name="startTime">ときにこのサイズ変更操作時に開始されました。</param>
        <param name="errors">プールで最後のサイズ変更を実行中に発生したエラーの詳細です。</param>
        <summary>
            ResizeOperationStatus クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResizeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ResizeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResizeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールで最後のサイズ変更を実行中に発生したエラーの詳細を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            最後のプール サイズ変更中にエラーが発生した場合にのみ、およびプールの allocationState が安定した場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of ComputeNodeDeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ComputeNodeDeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.NodeDeallocationOption" />
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
            既定値は requeue です。 使用可能な値が含まれます: 'キューに再登録'、'終了'、'TaskCompletion'、'RetainedData'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.ResizeTimeout" />
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
            取得またはプールから割り当てるコンピューティング ノードの場合のタイムアウトをプールまたはコンピューティング ノードの削除に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は、15 分です。 最小値は、5 分です。 5 分より小さい値を指定する場合、Batch service が; エラーを返しますREST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このサイズ変更操作が開始した時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.TargetDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.TargetDedicatedNodes" />
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
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.TargetLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus.TargetLowPriorityNodes" />
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
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>