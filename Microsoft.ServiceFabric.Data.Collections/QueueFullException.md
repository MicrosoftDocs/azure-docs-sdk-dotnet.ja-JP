<Type Name="QueueFullException" FullName="Microsoft.ServiceFabric.Data.Collections.QueueFullException">
  <TypeSignature Language="C#" Value="public class QueueFullException : System.Fabric.FabricTransientException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueFullException extends System.Fabric.FabricTransientException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueFullException&#xA;Inherits FabricTransientException" />
  <TypeSignature Language="F#" Value="type QueueFullException = class&#xA;    inherit FabricTransientException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricTransientException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            によってスローされた<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />ときのキューの容量に達しています。
            </summary>
    <remarks>
      <para>
            再試行が可能です。この例外を発生すると、呼び出し元必要がありますいくつかの待機時間追加エンキュー操作別デキューを発行する前に。
            </para>
      <para>
            キューの容量は現在実装されていません。
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />クラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException msg" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="msg">エラーを説明するメッセージ。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />指定したエラー メッセージを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string * Exception -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException (msg, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="msg">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</param>
        <summary>
            指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>