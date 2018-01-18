<Type Name="IPooledBuffer" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer">
  <TypeSignature Language="C#" Value="public interface IPooledBuffer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPooledBuffer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPooledBuffer" />
  <TypeSignature Language="F#" Value="type IPooledBuffer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ee81-101">IPooledBuffer クラスを表すインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="0ee81-101">Defines the interface that represents the IPooledBuffer class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public int ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Integer" />
      <MemberSignature Language="F#" Value="member this.ContentLength : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer.ContentLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ee81-102">取得または使用するバッファーの長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="0ee81-102">Gets or sets the length of the buffer used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Release">
      <MemberSignature Language="C#" Value="public bool Release ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Release() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer.Release" />
      <MemberSignature Language="VB.NET" Value="Public Function Release () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Release : unit -&gt; bool" Usage="iPooledBuffer.Release " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0ee81-103">プールにバッファーを解放します。</span><span class="sxs-lookup"><span data-stu-id="0ee81-103">Release the buffer to the Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public ArraySegment&lt;byte&gt; Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ArraySegment`1&lt;unsigned int8&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As ArraySegment(Of Byte)" />
      <MemberSignature Language="F#" Value="member this.Value : ArraySegment&lt;byte&gt;" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ArraySegment&lt;System.Byte&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0ee81-104">バッファーの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="0ee81-104">Gets the Value of the buffer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>