<Type Name="MethodResponse" FullName="Microsoft.Azure.Devices.Client.MethodResponse">
  <TypeSignature Language="C#" Value="public sealed class MethodResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MethodResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.MethodResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MethodResponse" />
  <TypeSignature Language="F#" Value="type MethodResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            データ構造体は、デバイス上でアクティビティをトリガーするために使用されるデバイス ツイン メソッドを表す
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MethodResponse (int status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.MethodResponse.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (status As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.MethodResponse : int -&gt; Microsoft.Azure.Devices.Client.MethodResponse" Usage="new Microsoft.Azure.Devices.Client.MethodResponse status" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="status">整数コード contianing メソッドは、状態を呼び出します。</param>
        <summary>
            入力バイト配列を本文として使用するコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MethodResponse (byte[] result, int status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] result, int32 status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.MethodResponse.#ctor(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (result As Byte(), status As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.MethodResponse : byte[] * int -&gt; Microsoft.Azure.Devices.Client.MethodResponse" Usage="new Microsoft.Azure.Devices.Client.MethodResponse (result, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="result" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
        <Parameter Name="status" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="result">メソッドの呼び出しによって返されるデータ。</param>
        <param name="status">成功または失敗を示す状態です。</param>
        <summary>
            戻り値のクラスの新しいインスタンスを作成し、ペイロードが正しい JSON であることを検証します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>