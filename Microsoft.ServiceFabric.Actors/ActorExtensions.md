<Type Name="ActorExtensions" FullName="Microsoft.ServiceFabric.Actors.ActorExtensions">
  <TypeSignature Language="C#" Value="public static class ActorExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ActorExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActorExtensions" />
  <TypeSignature Language="F#" Value="type ActorExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アクターの拡張メソッドを含むクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorId&lt;TIActor&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.ActorId GetActorId&lt;TIActor&gt; (this TIActor actor) where TIActor : Microsoft.ServiceFabric.Actors.IActor;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.ActorId GetActorId&lt;(class Microsoft.ServiceFabric.Actors.IActor) TIActor&gt;(!!TIActor actor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorExtensions.GetActorId``1(``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetActorId(Of TIActor As IActor) (actor As TIActor) As ActorId" />
      <MemberSignature Language="F#" Value="static member GetActorId : 'IActor -&gt; Microsoft.ServiceFabric.Actors.ActorId (requires 'IActor :&gt; Microsoft.ServiceFabric.Actors.IActor)" Usage="Microsoft.ServiceFabric.Actors.ActorExtensions.GetActorId actor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorId</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TIActor">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Actors.IActor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actor" Type="TIActor" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TIActor">アクター インターフェイスの型。</typeparam>
        <param name="actor">ActorId を取得するアクター オブジェクト。</param>
        <summary>
            取得<see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />アクターの/。&gt;
            </summary>
        <returns>
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />アクターです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActorReference">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.ActorReference GetActorReference (this Microsoft.ServiceFabric.Actors.IActor actor);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.ActorReference GetActorReference(class Microsoft.ServiceFabric.Actors.IActor actor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorExtensions.GetActorReference(Microsoft.ServiceFabric.Actors.IActor)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetActorReference (actor As IActor) As ActorReference" />
      <MemberSignature Language="F#" Value="static member GetActorReference : Microsoft.ServiceFabric.Actors.IActor -&gt; Microsoft.ServiceFabric.Actors.ActorReference" Usage="Microsoft.ServiceFabric.Actors.ActorExtensions.GetActorReference actor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.ActorReference</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actor" Type="Microsoft.ServiceFabric.Actors.IActor" RefType="this" />
      </Parameters>
      <Docs>
        <param name="actor">ActorReference を取得するアクター オブジェクト。</param>
        <summary>
            取得<see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" />アクターのです。
            </summary>
        <returns>
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorReference" />アクターです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>