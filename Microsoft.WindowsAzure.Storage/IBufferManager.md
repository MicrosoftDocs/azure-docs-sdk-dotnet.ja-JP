<Type Name="IBufferManager" FullName="Microsoft.WindowsAzure.Storage.IBufferManager">
  <TypeSignature Language="C#" Value="public interface IBufferManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBufferManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IBufferManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBufferManager" />
  <TypeSignature Language="F#" Value="type IBufferManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            クライアントを特定のサービス クライアントにバッファー マネージャーを提供できるようにするインターフェイスです。 このインターフェイスは、後でパターン化、 <see href="http://msdn.microsoft.com/en-us/library/system.servicemodel.channels.buffermanager.aspx">System.ServiceModel.Channels.BufferManager</see>クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDefaultBufferSize">
      <MemberSignature Language="C#" Value="public int GetDefaultBufferSize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 GetDefaultBufferSize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.GetDefaultBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDefaultBufferSize () As Integer" />
      <MemberSignature Language="F#" Value="abstract member GetDefaultBufferSize : unit -&gt; int" Usage="iBufferManager.GetDefaultBufferSize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            指定されたプールによって管理されているバッファーのバイト単位のサイズを取得します。 バッファー マネージャーが、クライアントによって要求された正確なサイズのバッファーを返す必要がありますに注意してください。
            </summary>
        <returns>指定されたプールによって管理されているバッファーのバイト単位のサイズ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnBuffer">
      <MemberSignature Language="C#" Value="public void ReturnBuffer (byte[] buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReturnBuffer(unsigned int8[] buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.ReturnBuffer(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReturnBuffer (buffer As Byte())" />
      <MemberSignature Language="F#" Value="abstract member ReturnBuffer : byte[] -&gt; unit" Usage="iBufferManager.ReturnBuffer buffer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="buffer">プールに返すバッファーを指定するバイト配列。</param>
        <summary>
            バッファーをプールに返します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Buffer の参照を null にすることはできません。</exception>
        <exception cref="T:System.ArgumentException">バッファーの長さには、プールのバッファー長プロパティは一致しません。</exception>
      </Docs>
    </Member>
    <Member MemberName="TakeBuffer">
      <MemberSignature Language="C#" Value="public byte[] TakeBuffer (int bufferSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] TakeBuffer(int32 bufferSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IBufferManager.TakeBuffer(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function TakeBuffer (bufferSize As Integer) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member TakeBuffer : int -&gt; byte[]" Usage="iBufferManager.TakeBuffer bufferSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bufferSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="bufferSize">要求するバッファーのサイズ (バイト単位)。</param>
        <summary>
            プールから指定したサイズ以上のバッファーを取得します。
            </summary>
        <returns>要求したバッファー サイズのバイト配列。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">指定された値<paramref name="bufferSize" />できません 0 未満です。</exception>
      </Docs>
    </Member>
  </Members>
</Type>