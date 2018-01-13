<Type Name="TransactionFaultedException" FullName="System.Fabric.TransactionFaultedException">
  <TypeSignature Language="C#" Value="public class TransactionFaultedException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TransactionFaultedException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionFaultedException" />
  <TypeSignature Language="VB.NET" Value="Public Class TransactionFaultedException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type TransactionFaultedException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>トランザクションの中、システムによって内部的に障害が発生したため失敗を示す例外です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransactionFaultedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : string -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>この例外の原因を説明するエラー メッセージ。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.TransactionFaultedException" />適切なメッセージを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransactionFaultedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para>スローされた例外に関するシリアル化されたオブジェクト データが含まれています。</para>
        </param>
        <param name="context">
          <para>ソースまたは転送先に関する文脈情報が含まれています。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.TransactionFaultedException" />シリアル化された状態からのクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransactionFaultedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionFaultedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.TransactionFaultedException : string * Exception -&gt; System.Fabric.TransactionFaultedException" Usage="new System.Fabric.TransactionFaultedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>この例外の原因を説明するエラー メッセージ。</para>
        </param>
        <param name="inner">
          <para>詳細な情報を提供する内部例外。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.TransactionFaultedException" />適切なメッセージを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>