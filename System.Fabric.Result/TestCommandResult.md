<Type Name="TestCommandResult" FullName="System.Fabric.Result.TestCommandResult">
  <TypeSignature Language="C#" Value="public abstract class TestCommandResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit TestCommandResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestCommandResult" />
  <TypeSignature Language="F#" Value="type TestCommandResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            結果オブジェクトの基本クラス。
            </summary>
    <remarks>
            このクラスには条件付きでは、例外が含まれています
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TestCommandResult ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.TestCommandResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            その他のテスト コマンド結果クラスから派生するための基本クラス。  このクラスでは、専用のプロパティは、例外です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.TestCommandResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.Result.TestCommandResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプロパティには、テスト コマンドが失敗した理由を示す例外が含まれています。  対応する TestCommandProgressState でエラーが発生しない限りが正しくありません。 
            </summary>
        <value>例外オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>