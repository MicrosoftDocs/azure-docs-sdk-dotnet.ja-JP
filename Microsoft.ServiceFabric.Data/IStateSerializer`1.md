<Type Name="IStateSerializer&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IStateSerializer&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateSerializer`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateSerializer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateSerializer(Of T)" />
  <TypeSignature Language="F#" Value="type IStateSerializer&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">シリアル化および逆シリアル化する型です。</typeparam>
    <summary>
             型のカスタム シリアライザーを表す<typeparamref name="T" />です。
             </summary>
    <remarks>
             使用して<see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />カスタム シリアライザーを登録します。
             </remarks>
    <example>
             この例では、読み取りと書き込みのオーバー ロードの実装だけで、対応するオーバー ロードを呼び出します。
             CurrentValue と baseValue パラメーターのプラットフォームで設定されていない、無視してください。
             <code>
             class Order
             {
                 public byte Warehouse { get; set; }
                 public short District { get; set; }
                 public int Customer { get; set; }
                 public long OrderNumber { get; set; }
             }
            
             class OrderSerializer : IStateSerializer&lt;Order&gt;
             {
                 void Write(Order value, BinaryWriter writer)
                 {
                     writer.Write(value.Warehouse);
                     writer.Write(value.District);
                     writer.Write(value.Customer);
                     writer.Write(value.OrderNumber);
                 }
            
                 Order Read(BinaryReader reader)
                 {
                     Order value = new Order();
            
                     value.Warehouse = reader.ReadByte();
                     value.District = reader.ReadInt16();
                     value.Customer = reader.ReadInt32();
                     value.OrderNumber = reader.ReadInt64();
            
                     return value;
                 }
            
                 void Write(Order currentValue, Order newValue, BinaryWriter writer)
                 {
                     this.Write(newValue, writer);
                 }
            
                 Order Read(Order baseValue, BinaryReader reader)
                 {
                     return this.Read(reader);
                 }
             }
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read binaryReader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="binaryReader"><see cref="T:System.IO.BinaryReader" />から逆シリアル化します。</param>
        <summary>
            逆シリアル化し、指定された<see cref="T:System.IO.BinaryReader" />に<typeparamref name="T" />です。
            </summary>
        <returns>逆シリアル化された値。</returns>
        <remarks>
            アクセスするとき、<see cref="T:System.IO.BinaryReader" />基本ストリームは、注意が必要、ストリーム内の位置を移動するときにします。
            読み取りは、ストリームの現在位置から始まるし、データの長さを足したもの、現在の位置で終了する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (T baseValue, System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(!T baseValue, class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(`0,System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : 'T * System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read (baseValue, binaryReader)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="baseValue">逆シリアル化の基本値。</param>
        <param name="binaryReader"><see cref="T:System.IO.BinaryReader" />から逆シリアル化します。</param>
        <summary>
            逆シリアル化し、指定された<see cref="T:System.IO.BinaryReader" />に<typeparamref name="T" />です。
            </summary>
        <returns>逆シリアル化された値。</returns>
        <remarks>
            アクセスするとき、<see cref="T:System.IO.BinaryReader" />基本ストリームは、注意が必要、ストリーム内の位置を移動するときにします。
            読み取りは、ストリームの現在位置から始まるし、データの長さを足したもの、現在の位置で終了する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T value, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T value, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (value, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="value">シリアル化する値。</param>
        <param name="binaryWriter"><see cref="T:System.IO.BinaryWriter" />にシリアル化します。</param>
        <summary>
            値をシリアル化およびに記録する、指定された<see cref="T:System.IO.BinaryWriter" />です。
            </summary>
        <remarks>
            アクセスするとき、<see cref="T:System.IO.BinaryWriter" />基本ストリームは、注意が必要、ストリーム内の位置を移動するときにします。
            書き込みは、ストリームの現在位置から開始して、データの長さを足したもの、現在の位置で終了します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T baseValue, T targetValue, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T baseValue, !T targetValue, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (baseValue, targetValue, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="targetValue" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="baseValue">シリアル化の基本値。</param>
        <param name="targetValue">シリアル化する値。</param>
        <param name="binaryWriter"><see cref="T:System.IO.BinaryWriter" />にシリアル化します。</param>
        <summary>
            オブジェクトをシリアル化およびに記録する、指定された<see cref="T:System.IO.BinaryWriter" />です。
            </summary>
        <remarks>
            アクセスするとき、<see cref="T:System.IO.BinaryWriter" />基本ストリームは、注意が必要、ストリーム内の位置を移動するときにします。
            書き込みは、ストリームの現在位置から開始して、データの長さを足したもの、現在の位置で終了します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>