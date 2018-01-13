<Type Name="EventDataBatch" FullName="Microsoft.Azure.EventHubs.EventDataBatch">
  <TypeSignature Language="C#" Value="public class EventDataBatch : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventDataBatch extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventDataBatch" />
  <TypeSignature Language="VB.NET" Value="Public Class EventDataBatch&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type EventDataBatch = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>EventData オブジェクト SendBatch または SendBatchAsync 呼び出しをするためのバッチを作成するためのヘルパー クラス。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventDataBatch (long maxSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxSizeInBytes As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventDataBatch : int64 -&gt; Microsoft.Azure.EventHubs.EventDataBatch" Usage="new Microsoft.Azure.EventHubs.EventDataBatch maxSizeInBytes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxSizeInBytes" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSizeInBytes">バッチで許可される最大サイズ</param>
        <summary>
            新しい <see cref="T:Microsoft.Azure.EventHubs.EventDataBatch" /> を作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventDataBatch.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.EventHubs.EventDataBatch.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バッチ内の現在のイベント数を取得します。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="eventDataBatch.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            EventDataBatch にアタッチされているリソースを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerable">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; ToEnumerable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; ToEnumerable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.ToEnumerable" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerable () As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ToEnumerable : unit -&gt; seq&lt;Microsoft.Azure.EventHubs.EventData&gt;" Usage="eventDataBatch.ToEnumerable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>バッチを SendBatchAsync メソッドによって受け付けられる EventData の IEnumerable オブジェクトに変換します。</summary>
        <returns>EventData の IEnumerable オブジェクトを返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventDataBatch.TryAdd(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.TryAdd : Microsoft.Azure.EventHubs.EventData -&gt; bool" Usage="eventDataBatch.TryAdd eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData">追加する <see cref="T:Microsoft.Azure.EventHubs.EventData" />。</param>
        <summary>イベント データをバッチのサイズ制限によって許可されている場合のバッチに追加しようとしています。</summary>
        <returns>バッチにイベント データが追加されているかどうかを示すブール値。</returns>
        <remarks>
            このメソッドは、バッチ、EventData オブジェクトおよび EventData オブジェクトを追加するかどうかに指定された上限のサイズを確認します。
            </remarks>
        <exception cref="T:System.ArgumentNullException">EventData が null の場合にスローされます。</exception>
        <exception cref="T:System.ObjectDisposedException">バッチが既に破棄されている場合にスローされます。</exception>
      </Docs>
    </Member>
  </Members>
</Type>