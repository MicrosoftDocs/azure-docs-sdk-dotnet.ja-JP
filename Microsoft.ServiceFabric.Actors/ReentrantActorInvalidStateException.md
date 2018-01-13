<Type Name="ReentrantActorInvalidStateException" FullName="Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException">
  <TypeSignature Language="C#" Value="public sealed class ReentrantActorInvalidStateException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReentrantActorInvalidStateException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReentrantActorInvalidStateException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type ReentrantActorInvalidStateException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            再入可能呼び出し中にアクターの状態が無効な場合は、アクター ランタイムによってスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException : string -&gt; Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" Usage="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>
            指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrantActorInvalidStateException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" Usage="new Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="inner">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</param>
        <summary>
            指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceFabric.Actors.ReentrantActorInvalidStateException" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>